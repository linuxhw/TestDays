Linux in Taiwan - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Taiwan.

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

Total: 507

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ASUS EXPERTBOOK B3302CEA    | [4e8ff6d2b4](https://linux-hardware.org/?probe=4e8ff6d2b4) | Dec 28, 2024 |
| Acer          | Aspire A15-41M              | [559864f811](https://linux-hardware.org/?probe=559864f811) | Dec 17, 2024 |
| MSI           | GF63 Thin 10SCXR            | [8c3060eca2](https://linux-hardware.org/?probe=8c3060eca2) | Dec 05, 2024 |
| Lenovo        | ThinkPad X280 20KESD1P00    | [181f001f7a](https://linux-hardware.org/?probe=181f001f7a) | Nov 30, 2024 |
| HP            | Pavilion Plus Laptop 14-... | [44489ab77c](https://linux-hardware.org/?probe=44489ab77c) | Nov 22, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [0a1c8d8087](https://linux-hardware.org/?probe=0a1c8d8087) | Nov 16, 2024 |
| ASUSTek       | X555LD                      | [c48f5a2ac0](https://linux-hardware.org/?probe=c48f5a2ac0) | Nov 13, 2024 |
| ASUSTek       | X555LD                      | [78ffea197c](https://linux-hardware.org/?probe=78ffea197c) | Nov 13, 2024 |
| Lenovo        | ThinkPad X230 23256V1       | [08af8a55a1](https://linux-hardware.org/?probe=08af8a55a1) | Nov 03, 2024 |
| Lenovo        | ThinkPad T460 20FNA06ACD    | [2444611c6c](https://linux-hardware.org/?probe=2444611c6c) | Oct 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [72cd76d953](https://linux-hardware.org/?probe=72cd76d953) | Oct 31, 2024 |
| Lenovo        | Yoga Pro 14s ASP9 83HN      | [414716466d](https://linux-hardware.org/?probe=414716466d) | Oct 30, 2024 |
| Insyde        | BayTrail                    | [83fca1d770](https://linux-hardware.org/?probe=83fca1d770) | Oct 17, 2024 |
| ASUSTek       | ZenBook UX431FN             | [54c4e9d189](https://linux-hardware.org/?probe=54c4e9d189) | Oct 17, 2024 |
| ASUSTek       | ZenBook UX431FN             | [d11c735e16](https://linux-hardware.org/?probe=d11c735e16) | Oct 17, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [d2c23ff5c0](https://linux-hardware.org/?probe=d2c23ff5c0) | Oct 15, 2024 |
| MSI           | CX420/CX420 MX              | [0b0e48a33a](https://linux-hardware.org/?probe=0b0e48a33a) | Oct 11, 2024 |
| MSI           | CX420/CX420 MX              | [9629b8daa3](https://linux-hardware.org/?probe=9629b8daa3) | Oct 11, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402XZ... | [bdfad7f253](https://linux-hardware.org/?probe=bdfad7f253) | Oct 09, 2024 |
| Acer          | Nitro AN515-56              | [7d9e391f34](https://linux-hardware.org/?probe=7d9e391f34) | Oct 09, 2024 |
| Lenovo        | ThinkPad X13 Gen 4 21EXS... | [fc5ef42d30](https://linux-hardware.org/?probe=fc5ef42d30) | Oct 08, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [c183bc0fcb](https://linux-hardware.org/?probe=c183bc0fcb) | Oct 05, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [9b63d50504](https://linux-hardware.org/?probe=9b63d50504) | Sep 26, 2024 |
| Lenovo        | ThinkPad X13 Gen 4 21EXS... | [9cec35ca8e](https://linux-hardware.org/?probe=9cec35ca8e) | Sep 26, 2024 |
| Acer          | Aspire E5-511G              | [eb212c1295](https://linux-hardware.org/?probe=eb212c1295) | Sep 21, 2024 |
| Acer          | Aspire E5-511G              | [0b1a846a69](https://linux-hardware.org/?probe=0b1a846a69) | Sep 17, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | [0464949c73](https://linux-hardware.org/?probe=0464949c73) | Sep 13, 2024 |
| Lenovo        | ThinkPad T430 2344A15       | [ef361a731b](https://linux-hardware.org/?probe=ef361a731b) | Sep 05, 2024 |
| Acer          | AOD255                      | [3dace1f171](https://linux-hardware.org/?probe=3dace1f171) | Sep 03, 2024 |
| Acer          | AOD255                      | [7d7265c514](https://linux-hardware.org/?probe=7d7265c514) | Sep 03, 2024 |
| HP            | Pavilion Plus Laptop 14-... | [14f6df4d7c](https://linux-hardware.org/?probe=14f6df4d7c) | Sep 01, 2024 |
| HP            | EliteBook 840 G1            | [64a0f64289](https://linux-hardware.org/?probe=64a0f64289) | Aug 28, 2024 |
| ASUSTek       | ROG Strix G733PY_G733PY_... | [d3a8fc48e3](https://linux-hardware.org/?probe=d3a8fc48e3) | Aug 22, 2024 |
| Lenovo        | IdeaPad S205 Brazos         | [e40f1ca18f](https://linux-hardware.org/?probe=e40f1ca18f) | Aug 15, 2024 |
| Acer          | Predator PH315-52           | [06245f5b64](https://linux-hardware.org/?probe=06245f5b64) | Aug 13, 2024 |
| Toshiba       | Satellite C50-A             | [5134fda652](https://linux-hardware.org/?probe=5134fda652) | Aug 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [9d7d8667c1](https://linux-hardware.org/?probe=9d7d8667c1) | Aug 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [4220088ba6](https://linux-hardware.org/?probe=4220088ba6) | Aug 01, 2024 |
| HP            | Pavilion Plus Laptop 14-... | [c38f999077](https://linux-hardware.org/?probe=c38f999077) | Jul 20, 2024 |
| Dell          | Latitude 5440               | [d2345051fa](https://linux-hardware.org/?probe=d2345051fa) | Jul 08, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C5Z... | [a9a670c9c7](https://linux-hardware.org/?probe=a9a670c9c7) | Jul 02, 2024 |
| Dynabook      | PORTEGE X40L-K              | [b186e464f5](https://linux-hardware.org/?probe=b186e464f5) | Jun 27, 2024 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [8b92f42365](https://linux-hardware.org/?probe=8b92f42365) | Jun 25, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7fdf0f1e50](https://linux-hardware.org/?probe=7fdf0f1e50) | Jun 23, 2024 |
| HP            | EliteBook 840 G5            | [d9aa22a316](https://linux-hardware.org/?probe=d9aa22a316) | Jun 08, 2024 |
| ASUSTek       | K46CM                       | [e7fb56dd1b](https://linux-hardware.org/?probe=e7fb56dd1b) | Jun 04, 2024 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [358ec467bf](https://linux-hardware.org/?probe=358ec467bf) | May 26, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [599aca7ecd](https://linux-hardware.org/?probe=599aca7ecd) | May 23, 2024 |
| Dell          | Inspiron 14 5425            | [50e62805a1](https://linux-hardware.org/?probe=50e62805a1) | May 23, 2024 |
| Lenovo        | ThinkPad X240 20AMA1P1TW    | [86dc66767e](https://linux-hardware.org/?probe=86dc66767e) | May 21, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [8f9768a181](https://linux-hardware.org/?probe=8f9768a181) | May 13, 2024 |
| ASUSTek       | GL553VW                     | [c51bf874e5](https://linux-hardware.org/?probe=c51bf874e5) | May 06, 2024 |
| HP            | Pavilion dm3                | [cb32e79169](https://linux-hardware.org/?probe=cb32e79169) | May 03, 2024 |
| Acer          | Aspire A514-55              | [3f25790115](https://linux-hardware.org/?probe=3f25790115) | Apr 30, 2024 |
| Dell          | Latitude 7490               | [12d9f9cce2](https://linux-hardware.org/?probe=12d9f9cce2) | Apr 27, 2024 |
| Samsung       | 940X3G/930X3G               | [7ae2ace4e3](https://linux-hardware.org/?probe=7ae2ace4e3) | Apr 17, 2024 |
| Samsung       | 940X3G/930X3G               | [ebcb51ed9c](https://linux-hardware.org/?probe=ebcb51ed9c) | Apr 16, 2024 |
| Acer          | Aspire E5-473G              | [e2f4ed0b39](https://linux-hardware.org/?probe=e2f4ed0b39) | Apr 03, 2024 |
| Acer          | Swift SF514-54GT            | [c0a1536935](https://linux-hardware.org/?probe=c0a1536935) | Mar 28, 2024 |
| HP            | Presario V3000 (RD462PA#... | [1fbccb2f58](https://linux-hardware.org/?probe=1fbccb2f58) | Mar 27, 2024 |
| Valve         | Galileo                     | [14e646cf21](https://linux-hardware.org/?probe=14e646cf21) | Mar 22, 2024 |
| Lenovo        | ThinkPad E14 20RA002LCD     | [0ee7bfce17](https://linux-hardware.org/?probe=0ee7bfce17) | Mar 22, 2024 |
| Valve         | Galileo                     | [cd0fb4513f](https://linux-hardware.org/?probe=cd0fb4513f) | Mar 21, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [83a22f435d](https://linux-hardware.org/?probe=83a22f435d) | Mar 21, 2024 |
| Apple         | MacBookAir6,1               | [8575151105](https://linux-hardware.org/?probe=8575151105) | Mar 14, 2024 |
| Genuine       | ZEUS 15H (GNB15H-9G650)     | [1cdfbc79db](https://linux-hardware.org/?probe=1cdfbc79db) | Mar 09, 2024 |
| Acer          | Aspire A515-57              | [7995029372](https://linux-hardware.org/?probe=7995029372) | Mar 06, 2024 |
| MECHREVO      | WUJIE14 PRO                 | [5b2bd502f2](https://linux-hardware.org/?probe=5b2bd502f2) | Mar 05, 2024 |
| HP            | Pavilion Plus Laptop 14-... | [a7108bda20](https://linux-hardware.org/?probe=a7108bda20) | Mar 05, 2024 |
| HP            | Pavilion Plus Laptop 14-... | [e14a9fae0a](https://linux-hardware.org/?probe=e14a9fae0a) | Mar 05, 2024 |
| Jumper        | EZpad                       | [526ffbb0c5](https://linux-hardware.org/?probe=526ffbb0c5) | Feb 28, 2024 |
| HP            | EliteBook 845 G7 Noteboo... | [caf3ea0d9a](https://linux-hardware.org/?probe=caf3ea0d9a) | Feb 20, 2024 |
| Sony          | SVT11215CWB                 | [89248167bd](https://linux-hardware.org/?probe=89248167bd) | Feb 18, 2024 |
| Acer          | Aspire VX5-591G             | [2fb2ff6aed](https://linux-hardware.org/?probe=2fb2ff6aed) | Feb 09, 2024 |
| ASUSTek       | X555LB                      | [5f19079461](https://linux-hardware.org/?probe=5f19079461) | Feb 06, 2024 |
| Gigabyte      | AORUS 5 SE                  | [09dc6d2649](https://linux-hardware.org/?probe=09dc6d2649) | Feb 03, 2024 |
| Acer          | Swift SF314-56              | [159a1c3a0f](https://linux-hardware.org/?probe=159a1c3a0f) | Feb 02, 2024 |
| LG Electro... | 16Z90Q-G.AA54C2             | [34806d0240](https://linux-hardware.org/?probe=34806d0240) | Jan 26, 2024 |
| LG Electro... | 16Z90Q-G.AA54C2             | [d847e907f7](https://linux-hardware.org/?probe=d847e907f7) | Jan 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [2ddefbdd81](https://linux-hardware.org/?probe=2ddefbdd81) | Jan 17, 2024 |
| HP            | Pavilion Plus Laptop 14-... | [8118029878](https://linux-hardware.org/?probe=8118029878) | Jan 06, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | [a46e855825](https://linux-hardware.org/?probe=a46e855825) | Jan 05, 2024 |
| HP            | ProBook 430 G2              | [c56ad1ad48](https://linux-hardware.org/?probe=c56ad1ad48) | Jan 02, 2024 |
| Acer          | Aspire SW5-012              | [efc348dbe0](https://linux-hardware.org/?probe=efc348dbe0) | Dec 31, 2023 |
| Google        | Delbin                      | [51a51a978d](https://linux-hardware.org/?probe=51a51a978d) | Dec 31, 2023 |
| Valve         | Galileo                     | [e21296767e](https://linux-hardware.org/?probe=e21296767e) | Dec 25, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [08e2f4eacc](https://linux-hardware.org/?probe=08e2f4eacc) | Dec 25, 2023 |
| Dynabook      | CS40L-HB                    | [da68e155cd](https://linux-hardware.org/?probe=da68e155cd) | Dec 20, 2023 |
| Acer          | Swift SF314-57G             | [b822161722](https://linux-hardware.org/?probe=b822161722) | Dec 19, 2023 |
| ASUSTek       | X450CC                      | [0af8e99fe6](https://linux-hardware.org/?probe=0af8e99fe6) | Dec 19, 2023 |
| ASUSTek       | X450CC                      | [238d032255](https://linux-hardware.org/?probe=238d032255) | Dec 19, 2023 |
| HP            | Pavilion 15                 | [8ea538629f](https://linux-hardware.org/?probe=8ea538629f) | Dec 17, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [5f19b6ce4f](https://linux-hardware.org/?probe=5f19b6ce4f) | Dec 16, 2023 |
| Acer          | Aspire V5-431               | [6e56833b2a](https://linux-hardware.org/?probe=6e56833b2a) | Dec 09, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [21847052d3](https://linux-hardware.org/?probe=21847052d3) | Dec 07, 2023 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | [68784031ca](https://linux-hardware.org/?probe=68784031ca) | Dec 05, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | [75603d3c20](https://linux-hardware.org/?probe=75603d3c20) | Dec 04, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | [b5086b8a65](https://linux-hardware.org/?probe=b5086b8a65) | Dec 01, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | [13d2cf2679](https://linux-hardware.org/?probe=13d2cf2679) | Nov 30, 2023 |
| CHIPHD        | NT125D                      | [44dab561a1](https://linux-hardware.org/?probe=44dab561a1) | Nov 21, 2023 |
| Dell          | Latitude 5440               | [107b422b2c](https://linux-hardware.org/?probe=107b422b2c) | Nov 20, 2023 |
| Dell          | Inspiron 7375               | [b72b8abe13](https://linux-hardware.org/?probe=b72b8abe13) | Nov 19, 2023 |
| Dell          | Latitude 5440               | [ed0b97c0a4](https://linux-hardware.org/?probe=ed0b97c0a4) | Nov 19, 2023 |
| Dell          | Latitude 5440               | [1f337ab4b1](https://linux-hardware.org/?probe=1f337ab4b1) | Nov 15, 2023 |
| Acer          | Aspire V3-471G              | [f027c1d470](https://linux-hardware.org/?probe=f027c1d470) | Nov 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [51e8be0935](https://linux-hardware.org/?probe=51e8be0935) | Nov 12, 2023 |
| MSI           | GL65 9SD                    | [d831c2e78e](https://linux-hardware.org/?probe=d831c2e78e) | Nov 06, 2023 |
| Acer          | Aspire A514-55              | [b9ad0e270f](https://linux-hardware.org/?probe=b9ad0e270f) | Nov 04, 2023 |
| Acer          | Aspire A514-55              | [985bf8e919](https://linux-hardware.org/?probe=985bf8e919) | Nov 01, 2023 |
| Dell          | G7 7590                     | [90cbef58c2](https://linux-hardware.org/?probe=90cbef58c2) | Oct 27, 2023 |
| Gigabyte      | AORUS 5 SE                  | [bf6473691f](https://linux-hardware.org/?probe=bf6473691f) | Oct 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9403CVA... | [eaffd30f59](https://linux-hardware.org/?probe=eaffd30f59) | Oct 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9403CVA... | [aafd893b0d](https://linux-hardware.org/?probe=aafd893b0d) | Oct 21, 2023 |
| MSI           | Alpha 17 C7VG               | [aa9ed0c963](https://linux-hardware.org/?probe=aa9ed0c963) | Oct 13, 2023 |
| MSI           | Alpha 17 C7VG               | [3cf39a38db](https://linux-hardware.org/?probe=3cf39a38db) | Oct 12, 2023 |
| Acer          | Swift SFX14-41G             | [ad1ae13902](https://linux-hardware.org/?probe=ad1ae13902) | Oct 11, 2023 |
| MSI           | GL65 9SD                    | [0e94bdcf1d](https://linux-hardware.org/?probe=0e94bdcf1d) | Oct 05, 2023 |
| MSI           | GL65 9SD                    | [32b5c9a302](https://linux-hardware.org/?probe=32b5c9a302) | Oct 05, 2023 |
| CHIPHD        | NT125D                      | [7e966b32de](https://linux-hardware.org/?probe=7e966b32de) | Sep 26, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | [3959de124c](https://linux-hardware.org/?probe=3959de124c) | Sep 14, 2023 |
| Toshiba       | Satellite L640              | [ac5a264fea](https://linux-hardware.org/?probe=ac5a264fea) | Sep 12, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [55b8608662](https://linux-hardware.org/?probe=55b8608662) | Sep 08, 2023 |
| Gigabyte      | GB-BKi3A-7100               | [40c832efb9](https://linux-hardware.org/?probe=40c832efb9) | Sep 04, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [b132ff749e](https://linux-hardware.org/?probe=b132ff749e) | Sep 01, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [ed4fafcabd](https://linux-hardware.org/?probe=ed4fafcabd) | Aug 31, 2023 |
| Sony          | VGN-C15TP_W                 | [591d0b778e](https://linux-hardware.org/?probe=591d0b778e) | Aug 30, 2023 |
| Sony          | VGN-C15TP_W                 | [a63433e04d](https://linux-hardware.org/?probe=a63433e04d) | Aug 25, 2023 |
| Acer          | Swift SFX14-41G             | [576626db19](https://linux-hardware.org/?probe=576626db19) | Aug 17, 2023 |
| Acer          | Aspire one                  | [47131c09b2](https://linux-hardware.org/?probe=47131c09b2) | Aug 16, 2023 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | [a94c8dc31f](https://linux-hardware.org/?probe=a94c8dc31f) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | [66c997fdec](https://linux-hardware.org/?probe=66c997fdec) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | [e57e76260c](https://linux-hardware.org/?probe=e57e76260c) | Aug 16, 2023 |
| ASUSTek       | UX31LA                      | [0695e3bb09](https://linux-hardware.org/?probe=0695e3bb09) | Aug 08, 2023 |
| MSI           | GL65 9SD                    | [b3ef4f1363](https://linux-hardware.org/?probe=b3ef4f1363) | Aug 07, 2023 |
| MSI           | GL65 9SD                    | [2539f4ad7a](https://linux-hardware.org/?probe=2539f4ad7a) | Aug 06, 2023 |
| MSI           | PS63 Modern 8M              | [96e7b96787](https://linux-hardware.org/?probe=96e7b96787) | Jul 27, 2023 |
| MSI           | GL65 9SD                    | [a3f9991e22](https://linux-hardware.org/?probe=a3f9991e22) | Jul 23, 2023 |
| MSI           | GL65 9SD                    | [57c6b0a7dd](https://linux-hardware.org/?probe=57c6b0a7dd) | Jul 15, 2023 |
| HP            | 250 G5 Notebook PC          | [030ecef01c](https://linux-hardware.org/?probe=030ecef01c) | Jul 08, 2023 |
| HP            | 250 G5 Notebook PC          | [56683a6866](https://linux-hardware.org/?probe=56683a6866) | Jul 08, 2023 |
| Google        | Cave                        | [cc3b1bb1a3](https://linux-hardware.org/?probe=cc3b1bb1a3) | Jun 24, 2023 |
| Google        | Cave                        | [199eb4826d](https://linux-hardware.org/?probe=199eb4826d) | Jun 24, 2023 |
| Acer          | Aspire A515-53G             | [430cfefc6a](https://linux-hardware.org/?probe=430cfefc6a) | Jun 21, 2023 |
| Lenovo        | ThinkPad X230 2324CD1       | [9ee6ed4144](https://linux-hardware.org/?probe=9ee6ed4144) | Jun 18, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | [cf08c655b9](https://linux-hardware.org/?probe=cf08c655b9) | Jun 17, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | [272d8de237](https://linux-hardware.org/?probe=272d8de237) | Jun 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 14IAP7 82S... | [dd5aaca858](https://linux-hardware.org/?probe=dd5aaca858) | Jun 15, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | [ba129cd52d](https://linux-hardware.org/?probe=ba129cd52d) | Jun 11, 2023 |
| Acidanther... | MacBookPro15,2              | [fb30b2eb35](https://linux-hardware.org/?probe=fb30b2eb35) | Jun 10, 2023 |
| Lenovo        | Z50-70 20354                | [05a473a2be](https://linux-hardware.org/?probe=05a473a2be) | Jun 06, 2023 |
| Apple         | MacBookPro7,1               | [e92db65759](https://linux-hardware.org/?probe=e92db65759) | Jun 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [a3089228b1](https://linux-hardware.org/?probe=a3089228b1) | Jun 05, 2023 |
| ASUSTek       | UX430UNR                    | [00ab711e0a](https://linux-hardware.org/?probe=00ab711e0a) | Jun 02, 2023 |
| Apple         | MacBookPro7,1               | [47ac3b9c43](https://linux-hardware.org/?probe=47ac3b9c43) | May 28, 2023 |
| Acer          | Swift SF514-54GT            | [dd79b67b18](https://linux-hardware.org/?probe=dd79b67b18) | May 27, 2023 |
| Apple         | MacBookPro7,1               | [324a8d5c88](https://linux-hardware.org/?probe=324a8d5c88) | May 22, 2023 |
| Apple         | MacBookPro7,1               | [88830e9fe8](https://linux-hardware.org/?probe=88830e9fe8) | May 22, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [fb58a4d348](https://linux-hardware.org/?probe=fb58a4d348) | May 14, 2023 |
| Lenovo        | IdeaPad 5 Pro 14IAP7 82S... | [02fb267cbc](https://linux-hardware.org/?probe=02fb267cbc) | May 07, 2023 |
| HP            | 250 G5 Notebook PC          | [e12a1d28ba](https://linux-hardware.org/?probe=e12a1d28ba) | May 06, 2023 |
| HP            | 250 G5 Notebook PC          | [4cb6025c16](https://linux-hardware.org/?probe=4cb6025c16) | May 03, 2023 |
| Apple         | MacBookPro11,1              | [7309ce024f](https://linux-hardware.org/?probe=7309ce024f) | Apr 25, 2023 |
| Valve         | Jupiter                     | [b2a94c7310](https://linux-hardware.org/?probe=b2a94c7310) | Apr 18, 2023 |
| Valve         | Jupiter                     | [965de2bcc4](https://linux-hardware.org/?probe=965de2bcc4) | Apr 11, 2023 |
| Lenovo        | IdeaPad 5 Pro 14IAP7 82S... | [c0901def8d](https://linux-hardware.org/?probe=c0901def8d) | Apr 10, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [c8173d40cd](https://linux-hardware.org/?probe=c8173d40cd) | Apr 09, 2023 |
| Dell          | Latitude 7490               | [01957ea955](https://linux-hardware.org/?probe=01957ea955) | Apr 07, 2023 |
| Toshiba       | Satellite L850              | [2635da1e14](https://linux-hardware.org/?probe=2635da1e14) | Apr 03, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | [649b881439](https://linux-hardware.org/?probe=649b881439) | Mar 25, 2023 |
| Insyde        | CherryTrail                 | [9e658f67a2](https://linux-hardware.org/?probe=9e658f67a2) | Mar 25, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | [a49ece0e6c](https://linux-hardware.org/?probe=a49ece0e6c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | [315f2256c6](https://linux-hardware.org/?probe=315f2256c6) | Mar 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [882f82cf2c](https://linux-hardware.org/?probe=882f82cf2c) | Mar 20, 2023 |
| Acer          | Aspire V3-571G              | [6aee8060e9](https://linux-hardware.org/?probe=6aee8060e9) | Mar 17, 2023 |
| Valve         | Jupiter                     | [db30abe51b](https://linux-hardware.org/?probe=db30abe51b) | Mar 13, 2023 |
| Toshiba       | Satellite C665              | [e95e34e3ba](https://linux-hardware.org/?probe=e95e34e3ba) | Mar 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7f3075e65e](https://linux-hardware.org/?probe=7f3075e65e) | Mar 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0S... | [2e864ba25e](https://linux-hardware.org/?probe=2e864ba25e) | Mar 08, 2023 |
| Valve         | Jupiter                     | [367bc56a15](https://linux-hardware.org/?probe=367bc56a15) | Mar 05, 2023 |
| Valve         | Jupiter                     | [c329f5f1c1](https://linux-hardware.org/?probe=c329f5f1c1) | Mar 05, 2023 |
| Valve         | Jupiter                     | [2143a36dc5](https://linux-hardware.org/?probe=2143a36dc5) | Feb 28, 2023 |
| Acer          | Swift SF514-54GT            | [dbccc5afa9](https://linux-hardware.org/?probe=dbccc5afa9) | Feb 23, 2023 |
| ASUSTek       | X202E                       | [6627e10e70](https://linux-hardware.org/?probe=6627e10e70) | Feb 19, 2023 |
| Dell          | Latitude E6320              | [467b45072e](https://linux-hardware.org/?probe=467b45072e) | Feb 19, 2023 |
| Lenovo        | ThinkPad X61 7673D13        | [b5399b39de](https://linux-hardware.org/?probe=b5399b39de) | Feb 19, 2023 |
| Acer          | Swift SF514-54GT            | [b7e961dae3](https://linux-hardware.org/?probe=b7e961dae3) | Feb 13, 2023 |
| Valve         | Jupiter                     | [e5f4ad1053](https://linux-hardware.org/?probe=e5f4ad1053) | Feb 12, 2023 |
| ASUSTek       | G73Sw                       | [42e7c32817](https://linux-hardware.org/?probe=42e7c32817) | Feb 06, 2023 |
| HP            | Notebook                    | [41f5c97a09](https://linux-hardware.org/?probe=41f5c97a09) | Feb 06, 2023 |
| AVITA         | NE14A2                      | [c5d9f8e3ac](https://linux-hardware.org/?probe=c5d9f8e3ac) | Feb 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [37059de5b7](https://linux-hardware.org/?probe=37059de5b7) | Jan 27, 2023 |
| MSI           | Alpha 15 B5EEK              | [d815a80782](https://linux-hardware.org/?probe=d815a80782) | Jan 24, 2023 |
| MSI           | Alpha 15 B5EEK              | [d2c9a02f60](https://linux-hardware.org/?probe=d2c9a02f60) | Jan 24, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [335275777a](https://linux-hardware.org/?probe=335275777a) | Jan 23, 2023 |
| Dell          | Latitude 7490               | [e40bb2f01f](https://linux-hardware.org/?probe=e40bb2f01f) | Jan 23, 2023 |
| Dell          | Latitude 7490               | [31789ae630](https://linux-hardware.org/?probe=31789ae630) | Jan 23, 2023 |
| HP            | ProBook 430 G2              | [24a0f33638](https://linux-hardware.org/?probe=24a0f33638) | Jan 22, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | [958ecc4388](https://linux-hardware.org/?probe=958ecc4388) | Jan 15, 2023 |
| Gigabyte      | GB-BKi3A-7100               | [8263d65b20](https://linux-hardware.org/?probe=8263d65b20) | Jan 08, 2023 |
| Gigabyte      | G5 GE                       | [d6a4584809](https://linux-hardware.org/?probe=d6a4584809) | Jan 07, 2023 |
| System76      | Lemur Pro                   | [36156d9aa7](https://linux-hardware.org/?probe=36156d9aa7) | Jan 07, 2023 |
| Dell          | Inspiron 13 5320            | [0007a36030](https://linux-hardware.org/?probe=0007a36030) | Jan 07, 2023 |
| Timi          | Mi Laptop Pro 15            | [7ea6f8ee94](https://linux-hardware.org/?probe=7ea6f8ee94) | Jan 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [9e535c1e8e](https://linux-hardware.org/?probe=9e535c1e8e) | Jan 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [2abdc57712](https://linux-hardware.org/?probe=2abdc57712) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [632515014d](https://linux-hardware.org/?probe=632515014d) | Dec 31, 2022 |
| MSI           | Modern 15 A5M               | [e0cb4d278d](https://linux-hardware.org/?probe=e0cb4d278d) | Dec 31, 2022 |
| MSI           | Modern 15 A5M               | [1e7182cb70](https://linux-hardware.org/?probe=1e7182cb70) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [ee7b1d707c](https://linux-hardware.org/?probe=ee7b1d707c) | Dec 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [7c8560a87e](https://linux-hardware.org/?probe=7c8560a87e) | Dec 25, 2022 |
| Acer          | Aspire 4750                 | [3256c282db](https://linux-hardware.org/?probe=3256c282db) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [9462031346](https://linux-hardware.org/?probe=9462031346) | Dec 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [7eb6658e3a](https://linux-hardware.org/?probe=7eb6658e3a) | Dec 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [7a14c8194f](https://linux-hardware.org/?probe=7a14c8194f) | Dec 20, 2022 |
| HUAWEI        | KLVL-WXX9                   | [a767e0fbf0](https://linux-hardware.org/?probe=a767e0fbf0) | Dec 16, 2022 |
| Lenovo        | ThinkPad W530 243858U       | [9dc4fb1abb](https://linux-hardware.org/?probe=9dc4fb1abb) | Dec 16, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [44484456f8](https://linux-hardware.org/?probe=44484456f8) | Dec 14, 2022 |
| ASUSTek       | PU403UA                     | [20007b4296](https://linux-hardware.org/?probe=20007b4296) | Dec 05, 2022 |
| Dell          | Vostro 5481                 | [6c58c07e64](https://linux-hardware.org/?probe=6c58c07e64) | Dec 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [55d95654c4](https://linux-hardware.org/?probe=55d95654c4) | Nov 30, 2022 |
| HP            | ProBook 430 G8 Notebook ... | [8a773e7358](https://linux-hardware.org/?probe=8a773e7358) | Nov 22, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [678cfec38b](https://linux-hardware.org/?probe=678cfec38b) | Nov 20, 2022 |
| MSI           | GE62 6QD                    | [3d2dd5419a](https://linux-hardware.org/?probe=3d2dd5419a) | Nov 18, 2022 |
| ASUSTek       | X550VX                      | [8e55592803](https://linux-hardware.org/?probe=8e55592803) | Nov 15, 2022 |
| Acer          | Swift SFX14-41G             | [a8023a34a0](https://linux-hardware.org/?probe=a8023a34a0) | Nov 11, 2022 |
| MSI           | U270DX                      | [2a68a6ba02](https://linux-hardware.org/?probe=2a68a6ba02) | Nov 10, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [52080bf6ef](https://linux-hardware.org/?probe=52080bf6ef) | Nov 09, 2022 |
| HP            | EliteBook x360 1030 G4      | [4fa71c1d6d](https://linux-hardware.org/?probe=4fa71c1d6d) | Nov 09, 2022 |
| Dell          | Inspiron 13 5320            | [9ac52708ad](https://linux-hardware.org/?probe=9ac52708ad) | Oct 17, 2022 |
| Intel Clie... | LAPRC710                    | [4a1e71b56a](https://linux-hardware.org/?probe=4a1e71b56a) | Oct 15, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [e940ddf8a7](https://linux-hardware.org/?probe=e940ddf8a7) | Oct 12, 2022 |
| ASUSTek       | PU403UA                     | [8bf4879487](https://linux-hardware.org/?probe=8bf4879487) | Oct 04, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CBA    | [4cad2a770c](https://linux-hardware.org/?probe=4cad2a770c) | Sep 30, 2022 |
| Lenovo        | ThinkPad T480s 20L7001YU... | [929514123f](https://linux-hardware.org/?probe=929514123f) | Sep 30, 2022 |
| Gigabyte      | AORUS 5 SE                  | [c188e2c5b5](https://linux-hardware.org/?probe=c188e2c5b5) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [5503282548](https://linux-hardware.org/?probe=5503282548) | Sep 20, 2022 |
| Acer          | Aspire A515-45              | [c0b89ea222](https://linux-hardware.org/?probe=c0b89ea222) | Aug 26, 2022 |
| Sony          | SVS15115FWB                 | [6844bd3288](https://linux-hardware.org/?probe=6844bd3288) | Aug 21, 2022 |
| Sony          | SVS15115FWB                 | [2fb1c4ab2d](https://linux-hardware.org/?probe=2fb1c4ab2d) | Aug 20, 2022 |
| Acer          | TravelMate P653-M           | [1e33abf031](https://linux-hardware.org/?probe=1e33abf031) | Aug 17, 2022 |
| Dell          | Inspiron 13 5320            | [cee0d5a717](https://linux-hardware.org/?probe=cee0d5a717) | Aug 14, 2022 |
| Dell          | Vostro 3525                 | [d6630abc3a](https://linux-hardware.org/?probe=d6630abc3a) | Aug 03, 2022 |
| ASUSTek       | K501LX                      | [8ea0c7daa9](https://linux-hardware.org/?probe=8ea0c7daa9) | Jul 30, 2022 |
| Acer          | Aspire A515-57G             | [a44d178033](https://linux-hardware.org/?probe=a44d178033) | Jul 30, 2022 |
| LG Electro... | LE50-5BC6H1                 | [010123b7d5](https://linux-hardware.org/?probe=010123b7d5) | Jul 26, 2022 |
| Acer          | Aspire K50-20               | [1f4543c39e](https://linux-hardware.org/?probe=1f4543c39e) | Jul 20, 2022 |
| Acer          | Aspire K50-20               | [3f0e68ecf5](https://linux-hardware.org/?probe=3f0e68ecf5) | Jul 20, 2022 |
| Acer          | TravelMate 8371             | [4af529e1c4](https://linux-hardware.org/?probe=4af529e1c4) | Jul 20, 2022 |
| Acer          | Aspire A515-45              | [4189e96860](https://linux-hardware.org/?probe=4189e96860) | Jul 19, 2022 |
| Dell          | Inspiron 5577               | [54fda2d2bc](https://linux-hardware.org/?probe=54fda2d2bc) | Jul 16, 2022 |
| Acer          | Aspire A515-57G             | [43a9aeb04d](https://linux-hardware.org/?probe=43a9aeb04d) | Jul 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [5f3670ea60](https://linux-hardware.org/?probe=5f3670ea60) | Jul 12, 2022 |
| Dell          | Vostro 3525                 | [2174c6314a](https://linux-hardware.org/?probe=2174c6314a) | Jul 11, 2022 |
| Dell          | Vostro 3525                 | [ff38c8714c](https://linux-hardware.org/?probe=ff38c8714c) | Jul 11, 2022 |
| Acer          | Swift SF514-54GT            | [554171275d](https://linux-hardware.org/?probe=554171275d) | Jul 07, 2022 |
| Acer          | Aspire A315-55G             | [e6d7a2a642](https://linux-hardware.org/?probe=e6d7a2a642) | Jun 30, 2022 |
| Lenovo        | ThinkPad T410 2518A37       | [4e15b37546](https://linux-hardware.org/?probe=4e15b37546) | Jun 30, 2022 |
| Dell          | Vostro 5625                 | [0a047126ba](https://linux-hardware.org/?probe=0a047126ba) | Jun 30, 2022 |
| MSI           | PE60 6QE                    | [4c7beba4e2](https://linux-hardware.org/?probe=4c7beba4e2) | Jun 29, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [43a27bb2dd](https://linux-hardware.org/?probe=43a27bb2dd) | Jun 23, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [f993d31672](https://linux-hardware.org/?probe=f993d31672) | Jun 22, 2022 |
| Dell          | Inspiron 14 5425            | [16e98704b5](https://linux-hardware.org/?probe=16e98704b5) | Jun 22, 2022 |
| Acer          | Aspire R7-371T              | [b791797ef3](https://linux-hardware.org/?probe=b791797ef3) | Jun 12, 2022 |
| Acer          | Aspire R7-371T              | [d573a80e21](https://linux-hardware.org/?probe=d573a80e21) | Jun 12, 2022 |
| Sony          | SVS15115FWB                 | [da41314683](https://linux-hardware.org/?probe=da41314683) | Jun 09, 2022 |
| Sony          | SVS15115FWB                 | [ab97043dbe](https://linux-hardware.org/?probe=ab97043dbe) | Jun 09, 2022 |
| Lenovo        | ThinkPad T410 2518A37       | [04e81b8b3f](https://linux-hardware.org/?probe=04e81b8b3f) | Jun 04, 2022 |
| Dell          | Latitude 5420               | [fedd7d10fb](https://linux-hardware.org/?probe=fedd7d10fb) | May 25, 2022 |
| Lex           | 3I610DW                     | [145688ea36](https://linux-hardware.org/?probe=145688ea36) | May 17, 2022 |
| Lex           | 3I610DW                     | [8baf27bb6a](https://linux-hardware.org/?probe=8baf27bb6a) | May 17, 2022 |
| Lex           | 3I610DW                     | [6c61eabd7c](https://linux-hardware.org/?probe=6c61eabd7c) | May 17, 2022 |
| Lex           | 3I610DW                     | [8a75530d17](https://linux-hardware.org/?probe=8a75530d17) | May 17, 2022 |
| ASUSTek       | K53SD                       | [0c04c6cb24](https://linux-hardware.org/?probe=0c04c6cb24) | May 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [1863683cb7](https://linux-hardware.org/?probe=1863683cb7) | May 06, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [1c94d4293a](https://linux-hardware.org/?probe=1c94d4293a) | May 02, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [b61c12247c](https://linux-hardware.org/?probe=b61c12247c) | May 02, 2022 |
| HP            | 15                          | [5d7a22faa6](https://linux-hardware.org/?probe=5d7a22faa6) | Apr 28, 2022 |
| Acer          | Aspire 1410                 | [0399a90ade](https://linux-hardware.org/?probe=0399a90ade) | Apr 23, 2022 |
| HP            | ProBook 430 G7              | [a084a48023](https://linux-hardware.org/?probe=a084a48023) | Apr 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [1a35138280](https://linux-hardware.org/?probe=1a35138280) | Apr 14, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [b6834625e2](https://linux-hardware.org/?probe=b6834625e2) | Apr 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [dccdc2c9f5](https://linux-hardware.org/?probe=dccdc2c9f5) | Apr 12, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f8c3b429a2](https://linux-hardware.org/?probe=f8c3b429a2) | Apr 09, 2022 |
| MSI           | GE70 0NC/GE70 0ND           | [369aac0795](https://linux-hardware.org/?probe=369aac0795) | Apr 09, 2022 |
| Acer          | Aspire 1410                 | [41ed1dae3d](https://linux-hardware.org/?probe=41ed1dae3d) | Apr 08, 2022 |
| MSI           | GE70 0NC/GE70 0ND           | [46b4d12526](https://linux-hardware.org/?probe=46b4d12526) | Apr 04, 2022 |
| ASUSTek       | X580VD                      | [192125a71f](https://linux-hardware.org/?probe=192125a71f) | Mar 29, 2022 |
| Acer          | Aspire 4750                 | [b89fa9f260](https://linux-hardware.org/?probe=b89fa9f260) | Mar 23, 2022 |
| Acer          | Aspire 4750                 | [ce61872360](https://linux-hardware.org/?probe=ce61872360) | Mar 23, 2022 |
| ASUSTek       | ZenBook UX433FN_U4300FN     | [0228881558](https://linux-hardware.org/?probe=0228881558) | Mar 18, 2022 |
| Acer          | Swift SF514-54GT            | [a170593a67](https://linux-hardware.org/?probe=a170593a67) | Mar 13, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [ea52efd6b6](https://linux-hardware.org/?probe=ea52efd6b6) | Mar 07, 2022 |
| MSI           | GV72 8RC                    | [60382ef4e5](https://linux-hardware.org/?probe=60382ef4e5) | Feb 25, 2022 |
| MSI           | GV72 8RC                    | [9cfacc57c2](https://linux-hardware.org/?probe=9cfacc57c2) | Feb 24, 2022 |
| MSI           | P65 Creator 9SD             | [093c9b9f41](https://linux-hardware.org/?probe=093c9b9f41) | Feb 24, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [076c8f6e01](https://linux-hardware.org/?probe=076c8f6e01) | Feb 23, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [85c09f63f0](https://linux-hardware.org/?probe=85c09f63f0) | Feb 23, 2022 |
| MSI           | P65 Creator 9SD             | [2782f833c9](https://linux-hardware.org/?probe=2782f833c9) | Feb 23, 2022 |
| HP            | DevX                        | [8dc3513586](https://linux-hardware.org/?probe=8dc3513586) | Feb 16, 2022 |
| HP            | DevX                        | [c6f8c8e65b](https://linux-hardware.org/?probe=c6f8c8e65b) | Feb 16, 2022 |
| CJSCOPE       | Z Series                    | [c594abda0a](https://linux-hardware.org/?probe=c594abda0a) | Feb 16, 2022 |
| Dell          | Latitude 5420               | [3c5cf0b4e7](https://linux-hardware.org/?probe=3c5cf0b4e7) | Feb 07, 2022 |
| Dell          | Latitude E7450              | [dd81e34279](https://linux-hardware.org/?probe=dd81e34279) | Feb 07, 2022 |
| Apple         | MacBookPro11,2              | [9d00f74637](https://linux-hardware.org/?probe=9d00f74637) | Feb 05, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | [30ddfbc611](https://linux-hardware.org/?probe=30ddfbc611) | Feb 03, 2022 |
| Intel Clie... | LAPBC710                    | [76dff27038](https://linux-hardware.org/?probe=76dff27038) | Feb 02, 2022 |
| Intel Clie... | LAPBC710                    | [a4c71279a4](https://linux-hardware.org/?probe=a4c71279a4) | Feb 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2a4563231b](https://linux-hardware.org/?probe=2a4563231b) | Feb 02, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | [992ee00a94](https://linux-hardware.org/?probe=992ee00a94) | Feb 02, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [0a04b2d1b1](https://linux-hardware.org/?probe=0a04b2d1b1) | Jan 31, 2022 |
| Acer          | Aspire V3-571G              | [43011b8d27](https://linux-hardware.org/?probe=43011b8d27) | Jan 30, 2022 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [e6af97e09c](https://linux-hardware.org/?probe=e6af97e09c) | Jan 29, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f653016830](https://linux-hardware.org/?probe=f653016830) | Jan 28, 2022 |
| ASUSTek       | PU403UA                     | [25ac7ce226](https://linux-hardware.org/?probe=25ac7ce226) | Jan 28, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [40d8a83107](https://linux-hardware.org/?probe=40d8a83107) | Jan 25, 2022 |
| Gigabyte      | P65                         | [4664ba9c41](https://linux-hardware.org/?probe=4664ba9c41) | Jan 17, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [fb4c60c7b1](https://linux-hardware.org/?probe=fb4c60c7b1) | Jan 14, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [0b302317eb](https://linux-hardware.org/?probe=0b302317eb) | Jan 14, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [94988f80b6](https://linux-hardware.org/?probe=94988f80b6) | Jan 09, 2022 |
| Dell          | Inspiron 5480               | [217737fa73](https://linux-hardware.org/?probe=217737fa73) | Dec 24, 2021 |
| Dell          | System Vostro 3450          | [482adf74be](https://linux-hardware.org/?probe=482adf74be) | Dec 21, 2021 |
| Dell          | System Vostro 3450          | [965939d30a](https://linux-hardware.org/?probe=965939d30a) | Dec 21, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [041e50f6a8](https://linux-hardware.org/?probe=041e50f6a8) | Dec 20, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [f9fbdf780e](https://linux-hardware.org/?probe=f9fbdf780e) | Dec 20, 2021 |
| Acer          | Aspire F5-573G              | [2e9fd50292](https://linux-hardware.org/?probe=2e9fd50292) | Dec 20, 2021 |
| Acer          | Aspire F5-573G              | [452b8c0ac4](https://linux-hardware.org/?probe=452b8c0ac4) | Dec 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [0f6fd49686](https://linux-hardware.org/?probe=0f6fd49686) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [aae6578de1](https://linux-hardware.org/?probe=aae6578de1) | Dec 16, 2021 |
| Unknown       | Unknown                     | [d07ab607e1](https://linux-hardware.org/?probe=d07ab607e1) | Dec 08, 2021 |
| Unknown       | Unknown                     | [8705e3aea1](https://linux-hardware.org/?probe=8705e3aea1) | Dec 07, 2021 |
| Dell          | Vostro 14 5410              | [ef6f4cf593](https://linux-hardware.org/?probe=ef6f4cf593) | Dec 05, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [2965330cf0](https://linux-hardware.org/?probe=2965330cf0) | Dec 02, 2021 |
| Dell          | Vostro 14 5410              | [6ab102bc84](https://linux-hardware.org/?probe=6ab102bc84) | Nov 30, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [a99a51f4e0](https://linux-hardware.org/?probe=a99a51f4e0) | Nov 23, 2021 |
| Acer          | Aspire E5-432G              | [d6fe7992f3](https://linux-hardware.org/?probe=d6fe7992f3) | Nov 21, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | [0315115315](https://linux-hardware.org/?probe=0315115315) | Nov 07, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [9ebc122525](https://linux-hardware.org/?probe=9ebc122525) | Nov 02, 2021 |
| HP            | ProBook 455 G7              | [1719b2dc9d](https://linux-hardware.org/?probe=1719b2dc9d) | Oct 30, 2021 |
| Acer          | AS1830                      | [bcef8c44a6](https://linux-hardware.org/?probe=bcef8c44a6) | Oct 26, 2021 |
| Lenovo        | ThinkPad E585 20KVCTO1WW    | [204598f27d](https://linux-hardware.org/?probe=204598f27d) | Oct 26, 2021 |
| Lenovo        | Z50-70 20354                | [22e290b148](https://linux-hardware.org/?probe=22e290b148) | Oct 08, 2021 |
| win elemen... | MBOX WS001                  | [95cb9076bc](https://linux-hardware.org/?probe=95cb9076bc) | Oct 04, 2021 |
| Acer          | TMP645-M                    | [c3daab516f](https://linux-hardware.org/?probe=c3daab516f) | Oct 03, 2021 |
| Toshiba       | PORTEGE R830                | [fbe6b1147d](https://linux-hardware.org/?probe=fbe6b1147d) | Sep 24, 2021 |
| HP            | Pavilion Laptop 14-bf1xx    | [6174640bb5](https://linux-hardware.org/?probe=6174640bb5) | Sep 23, 2021 |
| HP            | Pavilion Laptop 14-bf1xx    | [97a692e271](https://linux-hardware.org/?probe=97a692e271) | Sep 23, 2021 |
| MSI           | GS76 Stealth 11UH           | [0589c1c238](https://linux-hardware.org/?probe=0589c1c238) | Sep 18, 2021 |
| Lenovo        | ThinkPad X230 2324CD1       | [348eb8e841](https://linux-hardware.org/?probe=348eb8e841) | Sep 18, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [7725289d30](https://linux-hardware.org/?probe=7725289d30) | Sep 17, 2021 |
| Acer          | Swift SF514-55TA            | [b4ff244fa1](https://linux-hardware.org/?probe=b4ff244fa1) | Sep 14, 2021 |
| Acer          | Swift SF514-55TA            | [ca370567d0](https://linux-hardware.org/?probe=ca370567d0) | Sep 14, 2021 |
| Acer          | Swift SF514-55TA            | [c3a4ff2798](https://linux-hardware.org/?probe=c3a4ff2798) | Sep 12, 2021 |
| HP            | Pavilion dv7                | [6ed3caac2b](https://linux-hardware.org/?probe=6ed3caac2b) | Sep 10, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [ddb9671a92](https://linux-hardware.org/?probe=ddb9671a92) | Sep 09, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [b59922b47b](https://linux-hardware.org/?probe=b59922b47b) | Sep 09, 2021 |
| HP            | EliteBook 845 G8 Noteboo... | [1674818018](https://linux-hardware.org/?probe=1674818018) | Aug 23, 2021 |
| MSI           | Modern 14 B11M              | [63c6a56896](https://linux-hardware.org/?probe=63c6a56896) | Aug 22, 2021 |
| MSI           | Modern 14 B11M              | [f73a28166b](https://linux-hardware.org/?probe=f73a28166b) | Aug 22, 2021 |
| ASUSTek       | GL552VW                     | [b48b810fc9](https://linux-hardware.org/?probe=b48b810fc9) | Aug 21, 2021 |
| Acer          | Aspire A515-46              | [ad8f403c6d](https://linux-hardware.org/?probe=ad8f403c6d) | Aug 17, 2021 |
| AVITA         | NE14A2                      | [cd5b403f7b](https://linux-hardware.org/?probe=cd5b403f7b) | Aug 16, 2021 |
| Apple         | MacBookPro10,1              | [a1565d1576](https://linux-hardware.org/?probe=a1565d1576) | Aug 05, 2021 |
| Unknown       | Unknown                     | [d4db86e4ac](https://linux-hardware.org/?probe=d4db86e4ac) | Aug 05, 2021 |
| Unknown       | Unknown                     | [bcb72c9247](https://linux-hardware.org/?probe=bcb72c9247) | Aug 05, 2021 |
| Acer          | Swift SF313-52G             | [cf9d89a2f5](https://linux-hardware.org/?probe=cf9d89a2f5) | Jul 28, 2021 |
| AMI           | Unknown                     | [455466668e](https://linux-hardware.org/?probe=455466668e) | Jul 16, 2021 |
| Lenovo        | ThinkPad T510 4384CJ7       | [744091f92e](https://linux-hardware.org/?probe=744091f92e) | Jul 12, 2021 |
| Lenovo        | ThinkPad T510 4384CJ7       | [9f572c562f](https://linux-hardware.org/?probe=9f572c562f) | Jul 11, 2021 |
| ASUSTek       | E203NA                      | [a4aa015f4e](https://linux-hardware.org/?probe=a4aa015f4e) | Jul 09, 2021 |
| Dell          | Latitude 5420               | [7dc37e8b8c](https://linux-hardware.org/?probe=7dc37e8b8c) | Jul 09, 2021 |
| Dell          | Latitude 5420               | [1c11a8170f](https://linux-hardware.org/?probe=1c11a8170f) | Jul 09, 2021 |
| Acer          | TravelMate P653-M           | [f8509314e3](https://linux-hardware.org/?probe=f8509314e3) | Jun 27, 2021 |
| Toshiba       | Satellite L850              | [4632f9e875](https://linux-hardware.org/?probe=4632f9e875) | Jun 26, 2021 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [0624df0c82](https://linux-hardware.org/?probe=0624df0c82) | Jun 26, 2021 |
| Toshiba       | Satellite L850              | [a1f2e3a8a2](https://linux-hardware.org/?probe=a1f2e3a8a2) | Jun 23, 2021 |
| Acer          | Swift SF514-52T             | [9e0f7fa4a4](https://linux-hardware.org/?probe=9e0f7fa4a4) | Jun 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [6b7a4709ca](https://linux-hardware.org/?probe=6b7a4709ca) | Jun 20, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [b48bc39bc2](https://linux-hardware.org/?probe=b48bc39bc2) | Jun 20, 2021 |
| HP            | ProBook 430 G6              | [7bf43ae0d0](https://linux-hardware.org/?probe=7bf43ae0d0) | Jun 19, 2021 |
| HP            | ProBook 430 G6              | [9a4e288f49](https://linux-hardware.org/?probe=9a4e288f49) | Jun 19, 2021 |
| AMD           | Celadon-CZN                 | [cfad33c72b](https://linux-hardware.org/?probe=cfad33c72b) | Jun 16, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3RM0... | [cb69a79f5c](https://linux-hardware.org/?probe=cb69a79f5c) | Jun 14, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [5221d99db7](https://linux-hardware.org/?probe=5221d99db7) | Jun 10, 2021 |
| HP            | Unknown                     | [e59d9dcf16](https://linux-hardware.org/?probe=e59d9dcf16) | Jun 08, 2021 |
| MSI           | PE62 8RD                    | [30bb43121d](https://linux-hardware.org/?probe=30bb43121d) | Jun 01, 2021 |
| Lenovo        | V330-15IGM                  | [02894a3c1d](https://linux-hardware.org/?probe=02894a3c1d) | May 26, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [d63399b396](https://linux-hardware.org/?probe=d63399b396) | May 19, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | [fdbc72ed13](https://linux-hardware.org/?probe=fdbc72ed13) | May 05, 2021 |
| Toshiba       | Satellite L850              | [3f32e7ed1e](https://linux-hardware.org/?probe=3f32e7ed1e) | May 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0c83abd0f8](https://linux-hardware.org/?probe=0c83abd0f8) | Apr 11, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [ecbfcfa59d](https://linux-hardware.org/?probe=ecbfcfa59d) | Mar 23, 2021 |
| MSI           | GL65 9SD                    | [e3c6065246](https://linux-hardware.org/?probe=e3c6065246) | Mar 16, 2021 |
| Acer          | Aspire A515-56G             | [8bedf1b6da](https://linux-hardware.org/?probe=8bedf1b6da) | Mar 13, 2021 |
| Dell          | Latitude E7240              | [448e25eb93](https://linux-hardware.org/?probe=448e25eb93) | Mar 04, 2021 |
| ASUSTek       | K53SV                       | [743ce0ed2d](https://linux-hardware.org/?probe=743ce0ed2d) | Mar 03, 2021 |
| Dell          | Latitude E7240              | [adcc4f6449](https://linux-hardware.org/?probe=adcc4f6449) | Feb 25, 2021 |
| Lenovo        | IdeaPad S410 20301          | [90bb71374c](https://linux-hardware.org/?probe=90bb71374c) | Feb 14, 2021 |
| Acer          | Aspire 4755                 | [1ce988a158](https://linux-hardware.org/?probe=1ce988a158) | Jan 30, 2021 |
| Acer          | Aspire 5742G                | [b40787d632](https://linux-hardware.org/?probe=b40787d632) | Jan 24, 2021 |
| Acer          | Aspire 5742G                | [3cd78291fc](https://linux-hardware.org/?probe=3cd78291fc) | Jan 23, 2021 |
| Dell          | Inspiron 5537               | [b6a804b8b9](https://linux-hardware.org/?probe=b6a804b8b9) | Jan 10, 2021 |
| Dell          | Inspiron 5537               | [c88fbbaa7b](https://linux-hardware.org/?probe=c88fbbaa7b) | Jan 10, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [4758f7fd48](https://linux-hardware.org/?probe=4758f7fd48) | Jan 07, 2021 |
| HP            | ZBook 15 G6                 | [d4e634a972](https://linux-hardware.org/?probe=d4e634a972) | Dec 20, 2020 |
| ASUSTek       | PU403UA                     | [aee4dc13b7](https://linux-hardware.org/?probe=aee4dc13b7) | Dec 19, 2020 |
| Acer          | Aspire 4720Z                | [88bd8075b2](https://linux-hardware.org/?probe=88bd8075b2) | Dec 16, 2020 |
| Acer          | Aspire 4720Z                | [93cfeab463](https://linux-hardware.org/?probe=93cfeab463) | Dec 16, 2020 |
| Dell          | Inspiron 5437               | [db6ca10333](https://linux-hardware.org/?probe=db6ca10333) | Dec 02, 2020 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [f1f4d46046](https://linux-hardware.org/?probe=f1f4d46046) | Nov 26, 2020 |
| Acer          | Swift SF514-54GT            | [3301702747](https://linux-hardware.org/?probe=3301702747) | Nov 14, 2020 |
| Acer          | Swift SF514-54GT            | [70015c39cf](https://linux-hardware.org/?probe=70015c39cf) | Nov 14, 2020 |
| Acer          | Aspire 4755                 | [5251bda552](https://linux-hardware.org/?probe=5251bda552) | Nov 11, 2020 |
| Lenovo        | XiaoXinAir 15ARE 2021 82... | [2f285baee5](https://linux-hardware.org/?probe=2f285baee5) | Oct 23, 2020 |
| Lenovo        | ThinkPad Edge E531 68853... | [acbd72739e](https://linux-hardware.org/?probe=acbd72739e) | Oct 20, 2020 |
| Lenovo        | XiaoXinAir 15ARE 2021 82... | [d800296611](https://linux-hardware.org/?probe=d800296611) | Oct 16, 2020 |
| Acer          | Aspire A715-71G             | [cd05576b34](https://linux-hardware.org/?probe=cd05576b34) | Oct 04, 2020 |
| HP            | ProBook 455 G7              | [62da42ec3c](https://linux-hardware.org/?probe=62da42ec3c) | Sep 27, 2020 |
| HP            | G62                         | [c9c310542a](https://linux-hardware.org/?probe=c9c310542a) | Sep 27, 2020 |
| ASUSTek       | P2440UA                     | [4c196d17c7](https://linux-hardware.org/?probe=4c196d17c7) | Sep 25, 2020 |
| HP            | ProBook 455 G7              | [b2cdadc21e](https://linux-hardware.org/?probe=b2cdadc21e) | Sep 25, 2020 |
| Acer          | TravelMate P614-51TG        | [e0fbefb33a](https://linux-hardware.org/?probe=e0fbefb33a) | Sep 23, 2020 |
| HP            | Pavilion 11 x360 PC         | [558b4c758d](https://linux-hardware.org/?probe=558b4c758d) | Sep 18, 2020 |
| Acer          | Swift SF514-52T             | [570875f21d](https://linux-hardware.org/?probe=570875f21d) | Sep 12, 2020 |
| ASUSTek       | PU403UA                     | [bdae065e30](https://linux-hardware.org/?probe=bdae065e30) | Sep 11, 2020 |
| Acer          | TravelMate P633-M           | [a7fdf21400](https://linux-hardware.org/?probe=a7fdf21400) | Sep 11, 2020 |
| HP            | Pavilion 11 x360 PC         | [d2b7da6eeb](https://linux-hardware.org/?probe=d2b7da6eeb) | Sep 11, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | [72ffc70b7f](https://linux-hardware.org/?probe=72ffc70b7f) | Sep 07, 2020 |
| MSI           | GS63 7RE                    | [e95a9b9d20](https://linux-hardware.org/?probe=e95a9b9d20) | Sep 03, 2020 |
| MSI           | GS63 7RE                    | [c21eb43b7a](https://linux-hardware.org/?probe=c21eb43b7a) | Sep 03, 2020 |
| Acer          | Swift SF314-42              | [bec5ea27a1](https://linux-hardware.org/?probe=bec5ea27a1) | Aug 13, 2020 |
| Dell          | Inspiron 5759               | [6484055ab4](https://linux-hardware.org/?probe=6484055ab4) | Aug 10, 2020 |
| Intel         | JV10_CS                     | [f031e01d35](https://linux-hardware.org/?probe=f031e01d35) | Aug 09, 2020 |
| Dell          | XPS 13 9380                 | [5e3aebe1ec](https://linux-hardware.org/?probe=5e3aebe1ec) | Aug 02, 2020 |
| MSI           | CX62 6QD                    | [7484f1f7b0](https://linux-hardware.org/?probe=7484f1f7b0) | Jul 31, 2020 |
| Acer          | Aspire one                  | [534968996d](https://linux-hardware.org/?probe=534968996d) | Jul 24, 2020 |
| ASUSTek       | E203NA                      | [818318440a](https://linux-hardware.org/?probe=818318440a) | Jul 11, 2020 |
| Lenovo        | ThinkPad T420s 4171A18      | [aba119c0fe](https://linux-hardware.org/?probe=aba119c0fe) | Jul 03, 2020 |
| Lenovo        | ThinkPad T420s 4171A18      | [b23ac2b9df](https://linux-hardware.org/?probe=b23ac2b9df) | Jul 03, 2020 |
| HP            | Pavilion dv7                | [cdb63f485d](https://linux-hardware.org/?probe=cdb63f485d) | Jul 02, 2020 |
| HP            | Pavilion dv7                | [c130b59bb4](https://linux-hardware.org/?probe=c130b59bb4) | Jul 02, 2020 |
| MSI           | GS63 7RE                    | [2fe77551dc](https://linux-hardware.org/?probe=2fe77551dc) | Jun 30, 2020 |
| MSI           | PE72 8RD                    | [f91a312928](https://linux-hardware.org/?probe=f91a312928) | Jun 24, 2020 |
| ASUSTek       | UX30                        | [2b613d2551](https://linux-hardware.org/?probe=2b613d2551) | Jun 20, 2020 |
| MSI           | GS63 7RE                    | [3ddf7394d8](https://linux-hardware.org/?probe=3ddf7394d8) | Jun 18, 2020 |
| Acer          | Aspire E5-553G              | [7ac3604857](https://linux-hardware.org/?probe=7ac3604857) | Jun 14, 2020 |
| MSI           | GS63 7RE                    | [8f4591f672](https://linux-hardware.org/?probe=8f4591f672) | Jun 09, 2020 |
| HP            | ProBook 430 G3              | [208f945a87](https://linux-hardware.org/?probe=208f945a87) | Jun 02, 2020 |
| HUAWEI        | KPRC-WX0                    | [6e02cd7e95](https://linux-hardware.org/?probe=6e02cd7e95) | Jun 01, 2020 |
| HP            | ProBook 430 G3              | [e9ce68b09f](https://linux-hardware.org/?probe=e9ce68b09f) | May 12, 2020 |
| HP            | ProBook 430 G3              | [86b491fad9](https://linux-hardware.org/?probe=86b491fad9) | May 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [74697bc4d6](https://linux-hardware.org/?probe=74697bc4d6) | May 01, 2020 |
| ASUSTek       | X550VC                      | [e783786489](https://linux-hardware.org/?probe=e783786489) | May 01, 2020 |
| ASUSTek       | X550VC                      | [f46665f241](https://linux-hardware.org/?probe=f46665f241) | May 01, 2020 |
| ASUSTek       | X550VC                      | [c1036b76de](https://linux-hardware.org/?probe=c1036b76de) | May 01, 2020 |
| ASUSTek       | ASUSPRO B9440UAM            | [f77e6bd465](https://linux-hardware.org/?probe=f77e6bd465) | Apr 27, 2020 |
| ASUSTek       | ASUSPRO B9440UAM            | [96bb90cb10](https://linux-hardware.org/?probe=96bb90cb10) | Apr 27, 2020 |
| MSI           | GT63 Titan 9SG              | [c521df4d98](https://linux-hardware.org/?probe=c521df4d98) | Apr 25, 2020 |
| ASUSTek       | ZenBook 13 UX331UAL         | [188bcc68c0](https://linux-hardware.org/?probe=188bcc68c0) | Apr 11, 2020 |
| Dell          | Precision 7540              | [9b4e4569fc](https://linux-hardware.org/?probe=9b4e4569fc) | Apr 10, 2020 |
| ASUSTek       | TAICHI31                    | [e942e4a43e](https://linux-hardware.org/?probe=e942e4a43e) | Mar 17, 2020 |
| HP            | 250 G7 Notebook PC          | [d491751516](https://linux-hardware.org/?probe=d491751516) | Mar 09, 2020 |
| Acer          | Aspire one                  | [a956e8a20c](https://linux-hardware.org/?probe=a956e8a20c) | Mar 02, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [c291b5b947](https://linux-hardware.org/?probe=c291b5b947) | Feb 28, 2020 |
| Acer          | Aspire E5-572G              | [1215219438](https://linux-hardware.org/?probe=1215219438) | Feb 24, 2020 |
| Acer          | Aspire V5-591G              | [a3dd0ecbb3](https://linux-hardware.org/?probe=a3dd0ecbb3) | Feb 04, 2020 |
| Acer          | Aspire V5-591G              | [06a759a4a5](https://linux-hardware.org/?probe=06a759a4a5) | Feb 04, 2020 |
| Acer          | Predator PH317-53           | [553a1a04cd](https://linux-hardware.org/?probe=553a1a04cd) | Jan 21, 2020 |
| Acer          | Predator PH317-53           | [c515f18bdf](https://linux-hardware.org/?probe=c515f18bdf) | Jan 21, 2020 |
| ASUSTek       | S551LN                      | [1672f62e6a](https://linux-hardware.org/?probe=1672f62e6a) | Jan 18, 2020 |
| Acer          | Aspire one                  | [e5a2828fc4](https://linux-hardware.org/?probe=e5a2828fc4) | Jan 18, 2020 |
| Acer          | Aspire one                  | [5e43adead0](https://linux-hardware.org/?probe=5e43adead0) | Jan 10, 2020 |
| HP            | ProBook 4310s               | [e835f92f9b](https://linux-hardware.org/?probe=e835f92f9b) | Dec 05, 2019 |
| Vizio         | CT14                        | [2959768de4](https://linux-hardware.org/?probe=2959768de4) | Oct 28, 2019 |
| Vizio         | CT14                        | [83072575a5](https://linux-hardware.org/?probe=83072575a5) | Oct 28, 2019 |
| Acer          | Makalu                      | [00dd5c3407](https://linux-hardware.org/?probe=00dd5c3407) | Oct 19, 2019 |
| Acer          | Aspire 4745G                | [1842d2a0dd](https://linux-hardware.org/?probe=1842d2a0dd) | Oct 17, 2019 |
| Dell          | Inspiron 5437               | [3896fc1c82](https://linux-hardware.org/?probe=3896fc1c82) | Aug 18, 2019 |
| Lenovo        | ThinkPad T410 2537F34       | [25fa16d561](https://linux-hardware.org/?probe=25fa16d561) | Aug 17, 2019 |
| MSI           | GE70 2PE                    | [bba7f1b63c](https://linux-hardware.org/?probe=bba7f1b63c) | Aug 13, 2019 |
| MSI           | GE70 2PE                    | [1363b81c32](https://linux-hardware.org/?probe=1363b81c32) | Aug 11, 2019 |
| Sony          | SVP13229PWB                 | [3aa37419af](https://linux-hardware.org/?probe=3aa37419af) | Jul 23, 2019 |
| Unknown       | Unknown                     | [13f65e01c3](https://linux-hardware.org/?probe=13f65e01c3) | Jul 15, 2019 |
| Unknown       | Unknown                     | [7762bb952e](https://linux-hardware.org/?probe=7762bb952e) | Jul 09, 2019 |
| NEXCOM        | B537-I                      | [ce97b8b28b](https://linux-hardware.org/?probe=ce97b8b28b) | Jun 27, 2019 |
| ASUSTek       | ASUSPRO B9440UAM            | [56aa80a6c4](https://linux-hardware.org/?probe=56aa80a6c4) | Jun 20, 2019 |
| ASUSTek       | N53Jl                       | [0df8ea73f2](https://linux-hardware.org/?probe=0df8ea73f2) | Jun 14, 2019 |
| ASUSTek       | N53Jl                       | [0e4db84a2e](https://linux-hardware.org/?probe=0e4db84a2e) | Jun 14, 2019 |
| Acer          | Aspire E5-553G              | [41e017c4ae](https://linux-hardware.org/?probe=41e017c4ae) | Jun 02, 2019 |
| Sony          | VPCCB15FW                   | [f1c5d4c3c4](https://linux-hardware.org/?probe=f1c5d4c3c4) | May 17, 2019 |
| HP            | Pavilion Notebook           | [4452107fd7](https://linux-hardware.org/?probe=4452107fd7) | Apr 14, 2019 |
| Dell          | Vostro 15-3568              | [417000b97b](https://linux-hardware.org/?probe=417000b97b) | Apr 13, 2019 |
| HP            | Pavilion dv4                | [8f256add2b](https://linux-hardware.org/?probe=8f256add2b) | Apr 08, 2019 |
| HP            | ENVY Sleekbook 6 PC         | [7720ed3668](https://linux-hardware.org/?probe=7720ed3668) | Apr 08, 2019 |
| HP            | Compaq Presario CQ45        | [79588ac19b](https://linux-hardware.org/?probe=79588ac19b) | Apr 05, 2019 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [660901d55e](https://linux-hardware.org/?probe=660901d55e) | Jan 23, 2019 |
| Dell          | Inspiron 5442               | [2a64f0ce54](https://linux-hardware.org/?probe=2a64f0ce54) | Jan 22, 2019 |
| ASUSTek       | X555LB                      | [87f78b7843](https://linux-hardware.org/?probe=87f78b7843) | Dec 18, 2018 |
| ASUSTek       | X555LB                      | [02891bd4ea](https://linux-hardware.org/?probe=02891bd4ea) | Dec 18, 2018 |
| ASUSTek       | X555LB                      | [314622e44e](https://linux-hardware.org/?probe=314622e44e) | Dec 17, 2018 |
| ASUSTek       | X555LB                      | [062f1d59ce](https://linux-hardware.org/?probe=062f1d59ce) | Dec 17, 2018 |
| Dell          | XPS 13 9380                 | [d809782cbd](https://linux-hardware.org/?probe=d809782cbd) | Dec 12, 2018 |
| ASUSTek       | X510UQ                      | [5e508f8f1a](https://linux-hardware.org/?probe=5e508f8f1a) | Nov 09, 2018 |
| ASUSTek       | X510UQ                      | [5a5df173fb](https://linux-hardware.org/?probe=5a5df173fb) | Nov 09, 2018 |
| Acer          | Aspire 3820                 | [664332711f](https://linux-hardware.org/?probe=664332711f) | Nov 09, 2018 |
| Acer          | Aspire 3820                 | [7becdb1438](https://linux-hardware.org/?probe=7becdb1438) | Nov 09, 2018 |
| Dell          | XPS 13 9360                 | [8a7077867f](https://linux-hardware.org/?probe=8a7077867f) | Mar 10, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Taiwan/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 42        | 11.54%  |
| Ubuntu 22.04        | 36        | 9.89%   |
| Arch Rolling        | 21        | 5.77%   |
| Ubuntu 18.04        | 20        | 5.49%   |
| Debian 11           | 11        | 3.02%   |
| Fedora 37           | 10        | 2.75%   |
| Fedora 40           | 8         | 2.2%    |
| Pop!_OS 22.04       | 7         | 1.92%   |
| Pop!_OS 20.04       | 5         | 1.37%   |
| OpenMandriva 4.2    | 5         | 1.37%   |
| Kubuntu 22.04       | 5         | 1.37%   |
| Debian 12           | 5         | 1.37%   |
| Ubuntu 19.04        | 4         | 1.1%    |
| SteamOS 3.4.4       | 4         | 1.1%    |
| Linux Mint 21.1     | 4         | 1.1%    |
| Linux Mint 20.3     | 4         | 1.1%    |
| KDE neon 20.04      | 4         | 1.1%    |
| Fedora 38           | 4         | 1.1%    |
| Fedora 36           | 4         | 1.1%    |
| EndeavourOS Rolling | 4         | 1.1%    |
| Ubuntu 24.04        | 3         | 0.82%   |
| Ubuntu 23.10        | 3         | 0.82%   |
| Ubuntu 21.04        | 3         | 0.82%   |
| Ubuntu 19.10        | 3         | 0.82%   |
| Pop!_OS 21.04       | 3         | 0.82%   |
| OpenMandriva 4.3    | 3         | 0.82%   |
| OpenMandriva 23.01  | 3         | 0.82%   |
| Manjaro             | 3         | 0.82%   |
| Linux Mint 21.2     | 3         | 0.82%   |
| Fedora 41           | 3         | 0.82%   |
| Fedora 39           | 3         | 0.82%   |
| Fedora 34           | 3         | 0.82%   |
| Debian Testing      | 3         | 0.82%   |
| Debian              | 3         | 0.82%   |
| Arch                | 3         | 0.82%   |
| Zorin 17            | 2         | 0.55%   |
| Ubuntu 22.10        | 2         | 0.55%   |
| Ubuntu 20.10        | 2         | 0.55%   |
| Ubuntu 18.10        | 2         | 0.55%   |
| Ubuntu 16.04        | 2         | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 119       | 35.1%   |
| Fedora           | 36        | 10.62%  |
| Arch             | 24        | 7.08%   |
| Manjaro          | 23        | 6.78%   |
| Debian           | 20        | 5.9%    |
| OpenMandriva     | 19        | 5.6%    |
| Pop!_OS          | 17        | 5.01%   |
| Linux Mint       | 17        | 5.01%   |
| Kubuntu          | 9         | 2.65%   |
| SteamOS          | 6         | 1.77%   |
| Lubuntu          | 5         | 1.47%   |
| KDE neon         | 5         | 1.47%   |
| Zorin            | 4         | 1.18%   |
| EndeavourOS      | 4         | 1.18%   |
| Ubuntu MATE      | 3         | 0.88%   |
| Gentoo           | 3         | 0.88%   |
| Xubuntu          | 2         | 0.59%   |
| org.kde.Platform | 2         | 0.59%   |
| openSUSE         | 2         | 0.59%   |
| Nobara           | 2         | 0.59%   |
| Kali             | 2         | 0.59%   |
| Endless          | 2         | 0.59%   |
| Elementary       | 2         | 0.59%   |
| ArcoLinux        | 2         | 0.59%   |
| Ubuntu Unity     | 1         | 0.29%   |
| Ubuntu Studio    | 1         | 0.29%   |
| Ubuntu Budgie    | 1         | 0.29%   |
| Slackware        | 1         | 0.29%   |
| Rocky Linux      | 1         | 0.29%   |
| NixOS            | 1         | 0.29%   |
| MX               | 1         | 0.29%   |
| Kylin            | 1         | 0.29%   |
| CentOS           | 1         | 0.29%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 5         | 1.28%   |
| 5.13.0-valve36-1-neptune | 4         | 1.02%   |
| 6.8.0-45-generic         | 3         | 0.77%   |
| 6.8.0-40-generic         | 3         | 0.77%   |
| 6.5.0-9-generic          | 3         | 0.77%   |
| 6.5.0-35-generic         | 3         | 0.77%   |
| 6.5.0-14-generic         | 3         | 0.77%   |
| 6.1.1-desktop-1omv2290   | 3         | 0.77%   |
| 5.8.0-7630-generic       | 3         | 0.77%   |
| 5.4.0-42-generic         | 3         | 0.77%   |
| 5.3.0-46-generic         | 3         | 0.77%   |
| 5.3.0-40-generic         | 3         | 0.77%   |
| 5.16.7-desktop-1omv4003  | 3         | 0.77%   |
| 5.15.0-91-generic        | 3         | 0.77%   |
| 5.15.0-58-generic        | 3         | 0.77%   |
| 5.15.0-40-generic        | 3         | 0.77%   |
| 5.11.0-43-generic        | 3         | 0.77%   |
| 5.11.0-25-generic        | 3         | 0.77%   |
| 6.6.10-76060610-generic  | 2         | 0.51%   |
| 6.4.11-desktop-1omv2390  | 2         | 0.51%   |
| 6.2.6-desktop-1omv2390   | 2         | 0.51%   |
| 6.2.6-76060206-generic   | 2         | 0.51%   |
| 6.2.0-32-generic         | 2         | 0.51%   |
| 6.2.0-26-generic         | 2         | 0.51%   |
| 6.10.0-desktop-1omv2490  | 2         | 0.51%   |
| 6.1.0-13-amd64           | 2         | 0.51%   |
| 6.0.8-300.fc37.x86_64    | 2         | 0.51%   |
| 5.8.10-arch1-1           | 2         | 0.51%   |
| 5.8.0-53-generic         | 2         | 0.51%   |
| 5.8.0-43-generic         | 2         | 0.51%   |
| 5.4.64-1-MANJARO         | 2         | 0.51%   |
| 5.4.0-84-generic         | 2         | 0.51%   |
| 5.4.0-52-generic         | 2         | 0.51%   |
| 5.4.0-26-generic         | 2         | 0.51%   |
| 5.19.0-46-generic        | 2         | 0.51%   |
| 5.19.0-38-generic        | 2         | 0.51%   |
| 5.19.0-32-generic        | 2         | 0.51%   |
| 5.16.11-2-MANJARO        | 2         | 0.51%   |
| 5.15.0-53-generic        | 2         | 0.51%   |
| 5.15.0-48-generic        | 2         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 29        | 7.65%   |
| 5.4.0   | 25        | 6.6%    |
| 5.13.0  | 15        | 3.96%   |
| 6.5.0   | 14        | 3.69%   |
| 5.10.0  | 14        | 3.69%   |
| 5.8.0   | 13        | 3.43%   |
| 5.11.0  | 13        | 3.43%   |
| 6.8.0   | 11        | 2.9%    |
| 5.19.0  | 11        | 2.9%    |
| 4.18.0  | 10        | 2.64%   |
| 6.2.0   | 9         | 2.37%   |
| 4.15.0  | 9         | 2.37%   |
| 6.1.0   | 8         | 2.11%   |
| 5.3.0   | 7         | 1.85%   |
| 5.0.0   | 7         | 1.85%   |
| 6.1.1   | 6         | 1.58%   |
| 5.10.14 | 5         | 1.32%   |
| 6.2.6   | 4         | 1.06%   |
| 5.14.0  | 4         | 1.06%   |
| 6.0.0   | 3         | 0.79%   |
| 5.16.7  | 3         | 0.79%   |
| 5.16.11 | 3         | 0.79%   |
| 6.9.5   | 2         | 0.53%   |
| 6.8.8   | 2         | 0.53%   |
| 6.8.7   | 2         | 0.53%   |
| 6.7.6   | 2         | 0.53%   |
| 6.6.9   | 2         | 0.53%   |
| 6.6.2   | 2         | 0.53%   |
| 6.6.10  | 2         | 0.53%   |
| 6.5.6   | 2         | 0.53%   |
| 6.4.11  | 2         | 0.53%   |
| 6.2.9   | 2         | 0.53%   |
| 6.11.5  | 2         | 0.53%   |
| 6.10.7  | 2         | 0.53%   |
| 6.10.0  | 2         | 0.53%   |
| 6.1.9   | 2         | 0.53%   |
| 6.1.7   | 2         | 0.53%   |
| 6.1.52  | 2         | 0.53%   |
| 6.0.8   | 2         | 0.53%   |
| 5.8.10  | 2         | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 42        | 11.17%  |
| 5.4     | 28        | 7.45%   |
| 6.1     | 26        | 6.91%   |
| 5.10    | 24        | 6.38%   |
| 5.13    | 20        | 5.32%   |
| 6.2     | 19        | 5.05%   |
| 6.5     | 18        | 4.79%   |
| 5.8     | 18        | 4.79%   |
| 6.8     | 17        | 4.52%   |
| 5.19    | 15        | 3.99%   |
| 5.11    | 15        | 3.99%   |
| 6.6     | 11        | 2.93%   |
| 6.0     | 10        | 2.66%   |
| 4.18    | 10        | 2.66%   |
| 5.16    | 9         | 2.39%   |
| 4.15    | 9         | 2.39%   |
| 5.0     | 8         | 2.13%   |
| 6.10    | 7         | 1.86%   |
| 5.7     | 7         | 1.86%   |
| 5.3     | 7         | 1.86%   |
| 6.11    | 6         | 1.6%    |
| 5.14    | 6         | 1.6%    |
| 6.9     | 5         | 1.33%   |
| 6.7     | 5         | 1.33%   |
| 6.3     | 5         | 1.33%   |
| 5.17    | 5         | 1.33%   |
| 5.6     | 4         | 1.06%   |
| 6.4     | 3         | 0.8%    |
| 5.18    | 3         | 0.8%    |
| 5.12    | 3         | 0.8%    |
| 6.12    | 2         | 0.53%   |
| 5.9     | 2         | 0.53%   |
| 5.2     | 1         | 0.27%   |
| 4.4     | 1         | 0.27%   |
| 4.19    | 1         | 0.27%   |
| 4.14    | 1         | 0.27%   |
| 4.13    | 1         | 0.27%   |
| 4.10    | 1         | 0.27%   |
| 3.10    | 1         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 320       | 98.46%  |
| i686   | 5         | 1.54%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 165       | 48.1%   |
| KDE5             | 59        | 17.2%   |
| Unknown          | 42        | 12.24%  |
| XFCE             | 14        | 4.08%   |
| X-Cinnamon       | 14        | 4.08%   |
| KDE              | 8         | 2.33%   |
| MATE             | 7         | 2.04%   |
| LXQt             | 7         | 2.04%   |
| i3               | 4         | 1.17%   |
| KDE6             | 3         | 0.87%   |
| Pantheon         | 2         | 0.58%   |
| Openbox          | 2         | 0.58%   |
| LXDE             | 2         | 0.58%   |
| Hyprland         | 2         | 0.58%   |
| GNOME Flashback  | 2         | 0.58%   |
| Deepin           | 2         | 0.58%   |
| Unity            | 1         | 0.29%   |
| sway             | 1         | 0.29%   |
| qtile            | 1         | 0.29%   |
| niri             | 1         | 0.29%   |
| lightdm-xsession | 1         | 0.29%   |
| fluxbox          | 1         | 0.29%   |
| Budgie           | 1         | 0.29%   |
| bspwm            | 1         | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 219       | 64.99%  |
| Wayland | 85        | 25.22%  |
| Unknown | 25        | 7.42%   |
| Tty     | 8         | 2.37%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 124       | 36.26%  |
| SDDM    | 64        | 18.71%  |
| GDM3    | 57        | 16.67%  |
| GDM     | 55        | 16.08%  |
| LightDM | 32        | 9.36%   |
| TDM     | 4         | 1.17%   |
| SLiM    | 3         | 0.88%   |
| XDM     | 1         | 0.29%   |
| LXDM    | 1         | 0.29%   |
| GREETD  | 1         | 0.29%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 165       | 49.25%  |
| zh_TW   | 103       | 30.75%  |
| Unknown | 30        | 8.96%   |
| C       | 10        | 2.99%   |
| zh_CN   | 7         | 2.09%   |
| en_GB   | 5         | 1.49%   |
| ru_RU   | 3         | 0.9%    |
| lzh_TW  | 2         | 0.6%    |
| de_DE   | 2         | 0.6%    |
| zh_SG   | 1         | 0.3%    |
| zh_HK   | 1         | 0.3%    |
| POSIX   | 1         | 0.3%    |
| ja_JP   | 1         | 0.3%    |
| en_SG   | 1         | 0.3%    |
| en_IE   | 1         | 0.3%    |
| en_DK   | 1         | 0.3%    |
| C.UTF8  | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 203       | 61.33%  |
| BIOS | 128       | 38.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 236       | 71.08%  |
| Btrfs   | 45        | 13.55%  |
| Tmpfs   | 17        | 5.12%   |
| Overlay | 17        | 5.12%   |
| Xfs     | 8         | 2.41%   |
| Unknown | 4         | 1.2%    |
| Ext2    | 3         | 0.9%    |
| F2fs    | 1         | 0.3%    |
| Ext3    | 1         | 0.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 175       | 53.03%  |
| Unknown | 123       | 37.27%  |
| MBR     | 32        | 9.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 285       | 86.89%  |
| Yes       | 43        | 13.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 211       | 63.75%  |
| Yes       | 120       | 36.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Acer                 | 60        | 18.46%  |
| ASUSTek Computer     | 58        | 17.85%  |
| Lenovo               | 56        | 17.23%  |
| Hewlett-Packard      | 38        | 11.69%  |
| Dell                 | 27        | 8.31%   |
| MSI                  | 22        | 6.77%   |
| Valve                | 6         | 1.85%   |
| Toshiba              | 6         | 1.85%   |
| Sony                 | 5         | 1.54%   |
| Apple                | 5         | 1.54%   |
| Gigabyte Technology  | 4         | 1.23%   |
| LG Electronics       | 3         | 0.92%   |
| Unknown              | 3         | 0.92%   |
| Timi                 | 2         | 0.62%   |
| Samsung Electronics  | 2         | 0.62%   |
| Lex                  | 2         | 0.62%   |
| Intel Client Systems | 2         | 0.62%   |
| Insyde               | 2         | 0.62%   |
| HUAWEI               | 2         | 0.62%   |
| Google               | 2         | 0.62%   |
| Framework            | 2         | 0.62%   |
| Dynabook             | 2         | 0.62%   |
| AVITA                | 2         | 0.62%   |
| win element          | 1         | 0.31%   |
| Vizio                | 1         | 0.31%   |
| System76             | 1         | 0.31%   |
| NEXCOM               | 1         | 0.31%   |
| Jumper               | 1         | 0.31%   |
| Intel                | 1         | 0.31%   |
| Genuine              | 1         | 0.31%   |
| CJSCOPE              | 1         | 0.31%   |
| CHIPHD               | 1         | 0.31%   |
| AMI                  | 1         | 0.31%   |
| AMD                  | 1         | 0.31%   |
| Acidanthera          | 1         | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 5         | 1.54%   |
| Valve Jupiter                              | 4         | 1.23%   |
| Acer Swift SFX14-41G                       | 3         | 0.92%   |
| Valve Galileo                              | 2         | 0.62%   |
| Toshiba Satellite L850                     | 2         | 0.62%   |
| MSI GS63 7RE                               | 2         | 0.62%   |
| Lex 3I610DW                                | 2         | 0.62%   |
| Lenovo IdeaPad 5 14ALC05 82LM              | 2         | 0.62%   |
| HP ProBook 430 G8 Notebook PC              | 2         | 0.62%   |
| HP Pavilion dv7                            | 2         | 0.62%   |
| Framework Laptop 13 (AMD Ryzen 7040Series) | 2         | 0.62%   |
| Dell XPS 13 9380                           | 2         | 0.62%   |
| Dell Inspiron 14 5425                      | 2         | 0.62%   |
| AVITA NE14A2                               | 2         | 0.62%   |
| ASUS X555LB                                | 2         | 0.62%   |
| Acer Swift SF514-54GT                      | 2         | 0.62%   |
| Acer Swift SF514-52T                       | 2         | 0.62%   |
| Acer Aspire V3-571G                        | 2         | 0.62%   |
| Acer Aspire one                            | 2         | 0.62%   |
| Acer Aspire A514-55                        | 2         | 0.62%   |
| Acer Aspire 4755                           | 2         | 0.62%   |
| Acer Aspire 4750                           | 2         | 0.62%   |
| win element MBOX                           | 1         | 0.31%   |
| Vizio CT14                                 | 1         | 0.31%   |
| Toshiba Satellite L640                     | 1         | 0.31%   |
| Toshiba Satellite C665                     | 1         | 0.31%   |
| Toshiba Satellite C50-A                    | 1         | 0.31%   |
| Toshiba PORTEGE R830                       | 1         | 0.31%   |
| Timi Redmi Book Pro 15 2022                | 1         | 0.31%   |
| Timi Mi Laptop Pro 15                      | 1         | 0.31%   |
| System76 Lemur Pro                         | 1         | 0.31%   |
| Sony VPCCB15FW                             | 1         | 0.31%   |
| Sony VGN-C15TP_W                           | 1         | 0.31%   |
| Sony SVT11215CWB                           | 1         | 0.31%   |
| Sony SVS15115FWB                           | 1         | 0.31%   |
| Sony SVP13229PWB                           | 1         | 0.31%   |
| Samsung 940X3G/930X3G                      | 1         | 0.31%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B        | 1         | 0.31%   |
| NEXCOM B537-I                              | 1         | 0.31%   |
| MSI U270DX                                 | 1         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Acer Aspire        | 38        | 11.69%  |
| Lenovo ThinkPad    | 37        | 11.38%  |
| Acer Swift         | 12        | 3.69%   |
| Lenovo IdeaPad     | 11        | 3.38%   |
| HP Pavilion        | 10        | 3.08%   |
| Dell Inspiron      | 10        | 3.08%   |
| HP ProBook         | 9         | 2.77%   |
| ASUS Vivobook      | 9         | 2.77%   |
| ASUS ROG           | 9         | 2.77%   |
| HP EliteBook       | 6         | 1.85%   |
| Dell Latitude      | 6         | 1.85%   |
| ASUS ASUS          | 6         | 1.85%   |
| Toshiba Satellite  | 5         | 1.54%   |
| Dell Vostro        | 5         | 1.54%   |
| ASUS ZenBook       | 5         | 1.54%   |
| Unknown            | 5         | 1.54%   |
| Valve Jupiter      | 4         | 1.23%   |
| Acer TravelMate    | 4         | 1.23%   |
| Dell XPS           | 3         | 0.92%   |
| ASUS ASUSPRO       | 3         | 0.92%   |
| Valve Galileo      | 2         | 0.62%   |
| MSI Modern         | 2         | 0.62%   |
| MSI GS63           | 2         | 0.62%   |
| MSI GE70           | 2         | 0.62%   |
| MSI Alpha          | 2         | 0.62%   |
| Lex 3I610DW        | 2         | 0.62%   |
| Lenovo Yoga        | 2         | 0.62%   |
| Lenovo Legion      | 2         | 0.62%   |
| HP Compaq          | 2         | 0.62%   |
| HP 250             | 2         | 0.62%   |
| Framework Laptop   | 2         | 0.62%   |
| AVITA NE14A2       | 2         | 0.62%   |
| ASUS X555LB        | 2         | 0.62%   |
| Apple MacBookPro11 | 2         | 0.62%   |
| Acer Predator      | 2         | 0.62%   |
| win element MBOX   | 1         | 0.31%   |
| Vizio CT14         | 1         | 0.31%   |
| Toshiba PORTEGE    | 1         | 0.31%   |
| Timi Redmi         | 1         | 0.31%   |
| Timi Mi            | 1         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 40        | 12.31%  |
| 2022 | 31        | 9.54%   |
| 2019 | 29        | 8.92%   |
| 2020 | 27        | 8.31%   |
| 2018 | 25        | 7.69%   |
| 2017 | 20        | 6.15%   |
| 2014 | 20        | 6.15%   |
| 2012 | 20        | 6.15%   |
| 2011 | 19        | 5.85%   |
| 2015 | 17        | 5.23%   |
| 2013 | 15        | 4.62%   |
| 2023 | 14        | 4.31%   |
| 2016 | 14        | 4.31%   |
| 2010 | 9         | 2.77%   |
| 2009 | 9         | 2.77%   |
| 2008 | 8         | 2.46%   |
| 2024 | 3         | 0.92%   |
| 2007 | 2         | 0.62%   |
| 2006 | 2         | 0.62%   |
| 2004 | 1         | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 325       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 298       | 90.3%   |
| Enabled  | 32        | 9.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 322       | 99.08%  |
| Yes  | 3         | 0.92%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 88        | 26.67%  |
| 16.01-24.0  | 76        | 23.03%  |
| 8.01-16.0   | 61        | 18.48%  |
| 3.01-4.0    | 42        | 12.73%  |
| 32.01-64.0  | 29        | 8.79%   |
| 24.01-32.0  | 14        | 4.24%   |
| 64.01-256.0 | 8         | 2.42%   |
| 1.01-2.0    | 7         | 2.12%   |
| 2.01-3.0    | 3         | 0.91%   |
| 0.51-1.0    | 2         | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 103       | 28.53%  |
| 1.01-2.0   | 88        | 24.38%  |
| 4.01-8.0   | 77        | 21.33%  |
| 3.01-4.0   | 54        | 14.96%  |
| 8.01-16.0  | 22        | 6.09%   |
| 0.51-1.0   | 9         | 2.49%   |
| 16.01-24.0 | 3         | 0.83%   |
| 24.01-32.0 | 2         | 0.55%   |
| 0.01-0.5   | 2         | 0.55%   |
| 32.01-64.0 | 1         | 0.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 213       | 63.2%   |
| 2      | 101       | 29.97%  |
| 3      | 15        | 4.45%   |
| 0      | 5         | 1.48%   |
| 4      | 2         | 0.59%   |
| 5      | 1         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 259       | 79.45%  |
| Yes       | 67        | 20.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 244       | 74.85%  |
| No        | 82        | 25.15%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 310       | 95.38%  |
| No        | 15        | 4.62%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 287       | 87.77%  |
| No        | 40        | 12.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Taiwan  | 325       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Taipei            | 109       | 30.45%  |
| New Taipei        | 58        | 16.2%   |
| Taichung          | 31        | 8.66%   |
| Hsinchu           | 30        | 8.38%   |
| Taoyuan District  | 28        | 7.82%   |
| Kaohsiung City    | 25        | 6.98%   |
| Tainan City       | 10        | 2.79%   |
| Hsinchu County    | 9         | 2.51%   |
| Chang-hua         | 7         | 1.96%   |
| Zhongli District  | 4         | 1.12%   |
| Zhudong           | 3         | 0.84%   |
| Zhubei            | 3         | 0.84%   |
| Yunlin            | 3         | 0.84%   |
| Pingtung City     | 3         | 0.84%   |
| Nantou City       | 3         | 0.84%   |
| Keelung           | 3         | 0.84%   |
| Taoyuan City      | 2         | 0.56%   |
| Shulin District   | 2         | 0.56%   |
| Miaoli            | 2         | 0.56%   |
| Lugu              | 2         | 0.56%   |
| Daan              | 2         | 0.56%   |
| Banqiao           | 2         | 0.56%   |
| Yilan             | 1         | 0.28%   |
| Yangmei District  | 1         | 0.28%   |
| Xiawanzi          | 1         | 0.28%   |
| Tuniugou          | 1         | 0.28%   |
| Taichung City     | 1         | 0.28%   |
| Sanchong District | 1         | 0.28%   |
| Penghu County     | 1         | 0.28%   |
| Neihu             | 1         | 0.28%   |
| Linkou District   | 1         | 0.28%   |
| Jincheng          | 1         | 0.28%   |
| Fenjihu           | 1         | 0.28%   |
| Dawan             | 1         | 0.28%   |
| Chushui           | 1         | 0.28%   |
| Chiayi County     | 1         | 0.28%   |
| Chenggong         | 1         | 0.28%   |
| Buxin             | 1         | 0.28%   |
| Bao'an            | 1         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 51        | 65     | 11.41%  |
| WDC                         | 41        | 52     | 9.17%   |
| Sandisk                     | 32        | 42     | 7.16%   |
| SK hynix                    | 30        | 41     | 6.71%   |
| Seagate                     | 28        | 31     | 6.26%   |
| Crucial                     | 27        | 33     | 6.04%   |
| HGST                        | 26        | 28     | 5.82%   |
| Kingston                    | 25        | 32     | 5.59%   |
| Toshiba                     | 23        | 25     | 5.15%   |
| Unknown                     | 21        | 28     | 4.7%    |
| Micron Technology           | 16        | 18     | 3.58%   |
| Intel                       | 14        | 21     | 3.13%   |
| Hitachi                     | 13        | 14     | 2.91%   |
| Transcend                   | 6         | 7      | 1.34%   |
| Phison Electronics          | 6         | 8      | 1.34%   |
| KIOXIA                      | 6         | 9      | 1.34%   |
| Kingston Technology Company | 6         | 7      | 1.34%   |
| Micron/Crucial Technology   | 5         | 5      | 1.12%   |
| Unknown                     | 5         | 5      | 1.12%   |
| JMicron Technology          | 4         | 8      | 0.89%   |
| ASMT                        | 4         | 4      | 0.89%   |
| AGI                         | 4         | 4      | 0.89%   |
| A-DATA Technology           | 4         | 5      | 0.89%   |
| Team                        | 3         | 3      | 0.67%   |
| SPCC                        | 2         | 3      | 0.45%   |
| Silicon Motion              | 2         | 3      | 0.45%   |
| Realtek Semiconductor       | 2         | 2      | 0.45%   |
| Phison                      | 2         | 2      | 0.45%   |
| NeoTech                     | 2         | 2      | 0.45%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.45%   |
| LITEON                      | 2         | 2      | 0.45%   |
| Apple                       | 2         | 2      | 0.45%   |
| Apacer                      | 2         | 2      | 0.45%   |
| ZHITAI                      | 1         | 1      | 0.22%   |
| Yangtze Memory Technologies | 1         | 1      | 0.22%   |
| XPG                         | 1         | 1      | 0.22%   |
| USB3.2                      | 1         | 1      | 0.22%   |
| USB3.0                      | 1         | 1      | 0.22%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.22%   |
| Union Memory                | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB                             | 9         | 1.93%   |
| Crucial CT500MX500SSD1 500GB                         | 7         | 1.5%    |
| Crucial CT1000MX500SSD1 1TB                          | 7         | 1.5%    |
| Unknown MMC Card  64GB                               | 6         | 1.29%   |
| Toshiba MQ01ABD100 1TB                               | 5         | 1.07%   |
| Seagate ST1000LM035-1RK172 1TB                       | 5         | 1.07%   |
| Phison PS5013 E13 NVMe Controller 512GB              | 5         | 1.07%   |
| Crucial CT240BX500SSD1 240GB                         | 5         | 1.07%   |
| Unknown                                              | 5         | 1.07%   |
| Unknown MMC Card  32GB                               | 4         | 0.86%   |
| Toshiba MQ04ABF100 1TB                               | 4         | 0.86%   |
| SK hynix HFM512GD3JX016N 512GB                       | 4         | 0.86%   |
| Seagate ST1000LM049-2GH172 1TB                       | 4         | 0.86%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB      | 4         | 0.86%   |
| SanDisk NVMe SSD Drive 1TB                           | 4         | 0.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 4         | 0.86%   |
| HGST HTS545050A7E680 500GB                           | 4         | 0.86%   |
| HGST HTS541010A9E680 1TB                             | 4         | 0.86%   |
| SK hynix HFM512GD3JX013N 512GB                       | 3         | 0.64%   |
| SK hynix BC711 NVMe 512GB                            | 3         | 0.64%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 3         | 0.64%   |
| SanDisk NVMe SSD Drive 512GB                         | 3         | 0.64%   |
| SanDisk NVMe SSD Drive 256GB                         | 3         | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 3         | 0.64%   |
| Kingston SA400S37240G 240GB SSD                      | 3         | 0.64%   |
| Intel SSDPEKNU512GZ 512GB                            | 3         | 0.64%   |
| HGST HTS725050A7E630 500GB                           | 3         | 0.64%   |
| HGST HTS541010B7E610 1TB                             | 3         | 0.64%   |
| Crucial CT500MX500SSD4 500GB                         | 3         | 0.64%   |
| WDC WDS500G3X0C-00SJG0 500GB                         | 2         | 0.43%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                     | 2         | 0.43%   |
| WDC WD10SPZX-08Z10 1TB                               | 2         | 0.43%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 2         | 0.43%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                 | 2         | 0.43%   |
| Unknown MMC Card  512GB                              | 2         | 0.43%   |
| Unknown MMC Card  128GB                              | 2         | 0.43%   |
| SPCC Solid State Disk 240GB                          | 2         | 0.43%   |
| SK hynix NVMe SSD Drive 512GB                        | 2         | 0.43%   |
| Seagate ST9500420AS 500GB                            | 2         | 0.43%   |
| Seagate ST1000LX015-1U7172 1TB                       | 2         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 28        | 30     | 25.69%  |
| HGST               | 26        | 28     | 23.85%  |
| WDC                | 16        | 20     | 14.68%  |
| Toshiba            | 14        | 16     | 12.84%  |
| Hitachi            | 13        | 14     | 11.93%  |
| JMicron Technology | 3         | 7      | 2.75%   |
| ASMT               | 3         | 3      | 2.75%   |
| NeoTech            | 2         | 2      | 1.83%   |
| Unknown            | 1         | 1      | 0.92%   |
| StoreJet           | 1         | 2      | 0.92%   |
| Fujitsu            | 1         | 1      | 0.92%   |
| External           | 1         | 1      | 0.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 25        | 30     | 19.53%  |
| Samsung Electronics | 13        | 15     | 10.16%  |
| Kingston            | 13        | 15     | 10.16%  |
| SanDisk             | 12        | 15     | 9.38%   |
| WDC                 | 8         | 10     | 6.25%   |
| Transcend           | 6         | 7      | 4.69%   |
| Toshiba             | 6         | 6      | 4.69%   |
| Micron Technology   | 5         | 7      | 3.91%   |
| Intel               | 5         | 10     | 3.91%   |
| SK hynix            | 4         | 4      | 3.13%   |
| A-DATA Technology   | 4         | 5      | 3.13%   |
| Unknown             | 3         | 3      | 2.34%   |
| Team                | 2         | 2      | 1.56%   |
| SPCC                | 2         | 3      | 1.56%   |
| LITEON              | 2         | 2      | 1.56%   |
| Apple               | 2         | 2      | 1.56%   |
| Apacer              | 2         | 2      | 1.56%   |
| AGI                 | 2         | 2      | 1.56%   |
| Plextor             | 1         | 1      | 0.78%   |
| Patriot             | 1         | 1      | 0.78%   |
| OCZ                 | 1         | 1      | 0.78%   |
| NT-512              | 1         | 1      | 0.78%   |
| MyDigitalSSD        | 1         | 1      | 0.78%   |
| MX                  | 1         | 1      | 0.78%   |
| LITEONIT            | 1         | 1      | 0.78%   |
| Kingchuxing         | 1         | 1      | 0.78%   |
| FORESEE             | 1         | 1      | 0.78%   |
| Aura                | 1         | 1      | 0.78%   |
| ASMT                | 1         | 1      | 0.78%   |
| Acer                | 1         | 2      | 0.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 159       | 233    | 38.88%  |
| SSD     | 117       | 153    | 28.61%  |
| HDD     | 103       | 125    | 25.18%  |
| MMC     | 20        | 27     | 4.89%   |
| Unknown | 10        | 11     | 2.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 188       | 262    | 48.45%  |
| NVMe | 159       | 233    | 40.98%  |
| SAS  | 21        | 27     | 5.41%   |
| MMC  | 20        | 27     | 5.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 130       | 170    | 59.36%  |
| 0.51-1.0   | 82        | 99     | 37.44%  |
| 1.01-2.0   | 6         | 8      | 2.74%   |
| 4.01-10.0  | 1         | 1      | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 92        | 26.51%  |
| 101-250        | 89        | 25.65%  |
| 501-1000       | 59        | 17%     |
| 1-20           | 29        | 8.36%   |
| 1001-2000      | 22        | 6.34%   |
| 51-100         | 20        | 5.76%   |
| 21-50          | 13        | 3.75%   |
| 2001-3000      | 10        | 2.88%   |
| Unknown        | 9         | 2.59%   |
| More than 3000 | 4         | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 143       | 39.83%  |
| 101-250        | 53        | 14.76%  |
| 21-50          | 48        | 13.37%  |
| 51-100         | 43        | 11.98%  |
| 251-500        | 40        | 11.14%  |
| 501-1000       | 16        | 4.46%   |
| Unknown        | 9         | 2.51%   |
| 2001-3000      | 3         | 0.84%   |
| 1001-2000      | 3         | 0.84%   |
| More than 3000 | 1         | 0.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB                                      | 2         | 2      | 10%     |
| WDC WDS480G2G0B-00EPW0 480GB SSD                                | 1         | 1      | 5%      |
| WDC WDS240G2G0B-00EPW0 240GB SSD                                | 1         | 1      | 5%      |
| WDC WD3200BEKT-60V5T1 320GB                                     | 1         | 1      | 5%      |
| WDC WD1600BEVT-22A23T0 160GB                                    | 1         | 1      | 5%      |
| Transcend TS240GMTS420S 240GB SSD                               | 1         | 1      | 5%      |
| Toshiba MQ01ABD075 752GB                                        | 1         | 1      | 5%      |
| Team TM8FP4004T 4TB                                             | 1         | 1      | 5%      |
| SK hynix PC711 HFS512GDE9X073N 512GB                            | 1         | 1      | 5%      |
| SK hynix HFS128G39MNC-2300A 128GB SSD                           | 1         | 1      | 5%      |
| Seagate ST9500325AS 500GB                                       | 1         | 1      | 5%      |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 512GB | 1         | 1      | 5%      |
| Samsung Electronics MZVPV256HDGL-00000 256GB                    | 1         | 1      | 5%      |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD                  | 1         | 1      | 5%      |
| Hitachi HTS722080K9SA00 80GB                                    | 1         | 1      | 5%      |
| Hitachi HTS545050A7E380 500GB                                   | 1         | 1      | 5%      |
| HGST HTS725050A7E630 500GB                                      | 1         | 1      | 5%      |
| ASMT 2115 320GB                                                 | 1         | 1      | 5%      |
| Apacer AS350 256GB SSD                                          | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 20%     |
| HGST                | 3         | 3      | 15%     |
| SK hynix            | 2         | 2      | 10%     |
| Samsung Electronics | 2         | 2      | 10%     |
| Hitachi             | 2         | 2      | 10%     |
| Transcend           | 1         | 1      | 5%      |
| Toshiba             | 1         | 1      | 5%      |
| Team                | 1         | 1      | 5%      |
| Seagate             | 1         | 1      | 5%      |
| Micron Technology   | 1         | 1      | 5%      |
| ASMT                | 1         | 1      | 5%      |
| Apacer              | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 3         | 3      | 30%     |
| WDC     | 2         | 2      | 20%     |
| Hitachi | 2         | 2      | 20%     |
| Toshiba | 1         | 1      | 10%     |
| Seagate | 1         | 1      | 10%     |
| ASMT    | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 50%     |
| SSD  | 6         | 6      | 30%     |
| NVMe | 4         | 4      | 20%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| HGST HTS541010A9E680 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 173       | 283    | 48.73%  |
| Works    | 162       | 245    | 45.63%  |
| Malfunc  | 19        | 20     | 5.35%   |
| Failed   | 1         | 1      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 213       | 51.45%  |
| Samsung Electronics                     | 42        | 10.14%  |
| SanDisk                                 | 34        | 8.21%   |
| AMD                                     | 27        | 6.52%   |
| SK hynix                                | 26        | 6.28%   |
| Kingston Technology Company             | 17        | 4.11%   |
| Micron Technology                       | 12        | 2.9%    |
| Toshiba America Info Systems            | 7         | 1.69%   |
| Micron/Crucial Technology               | 7         | 1.69%   |
| Phison Electronics                      | 6         | 1.45%   |
| KIOXIA                                  | 4         | 0.97%   |
| Realtek Semiconductor                   | 3         | 0.72%   |
| Silicon Motion                          | 2         | 0.48%   |
| Shenzhen Unionmemory Information System | 2         | 0.48%   |
| Nvidia                                  | 2         | 0.48%   |
| MAXIO Technology (Hangzhou)             | 2         | 0.48%   |
| Yangtze Memory Technologies             | 1         | 0.24%   |
| Union Memory (Shenzhen)                 | 1         | 0.24%   |
| Solidigm                                | 1         | 0.24%   |
| Solid State Storage Technology          | 1         | 0.24%   |
| Marvell Technology Group                | 1         | 0.24%   |
| Lite-On Technology                      | 1         | 0.24%   |
| Biwin Storage Technology                | 1         | 0.24%   |
| ADATA Technology                        | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 28        | 6.41%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 25        | 5.72%   |
| Intel Volume Management Device NVMe RAID Controller                            | 23        | 5.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 22        | 5.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 16        | 3.66%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 16        | 3.66%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 16        | 3.66%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 15        | 3.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 3.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 12        | 2.75%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 11        | 2.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 2.29%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 10        | 2.29%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 9         | 2.06%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 2.06%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 8         | 1.83%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 8         | 1.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 1.6%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.37%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 6         | 1.37%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 5         | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.14%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 5         | 1.14%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 4         | 0.92%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 4         | 0.92%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                     | 4         | 0.92%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 4         | 0.92%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 4         | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 0.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 0.92%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.69%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 0.69%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 0.69%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 3         | 0.69%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 3         | 0.69%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 0.69%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 3         | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 0.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 211       | 51.09%  |
| NVMe | 160       | 38.74%  |
| RAID | 33        | 7.99%   |
| IDE  | 9         | 2.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 261       | 80.31%  |
| AMD    | 64        | 19.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz          | 10        | 3.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 8         | 2.46%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 7         | 2.15%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 7         | 2.15%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 7         | 2.15%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 6         | 1.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 6         | 1.85%   |
| Intel Core i5-5200U CPU @ 2.20GHz          | 6         | 1.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 5         | 1.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 5         | 1.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 5         | 1.54%   |
| Intel 12th Gen Core i5-12500H              | 5         | 1.54%   |
| AMD Custom APU 0405                        | 5         | 1.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 4         | 1.23%   |
| Intel Core i7-4500U CPU @ 1.80GHz          | 4         | 1.23%   |
| Intel Core i5-3230M CPU @ 2.60GHz          | 4         | 1.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 4         | 1.23%   |
| Intel 12th Gen Core i5-1235U               | 4         | 1.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 3         | 0.92%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz         | 3         | 0.92%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 3         | 0.92%   |
| Intel Core i5-8300H CPU @ 2.30GHz          | 3         | 0.92%   |
| Intel Core i5-4210U CPU @ 1.70GHz          | 3         | 0.92%   |
| Intel Core i5-4200U CPU @ 1.60GHz          | 3         | 0.92%   |
| Intel Core i5-3317U CPU @ 1.70GHz          | 3         | 0.92%   |
| Intel Celeron N4020 CPU @ 1.10GHz          | 3         | 0.92%   |
| Intel 12th Gen Core i7-12700H              | 3         | 0.92%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz    | 3         | 0.92%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 3         | 0.92%   |
| AMD Ryzen 7 5800U with Radeon Graphics     | 3         | 0.92%   |
| AMD Ryzen 7 5700U with Radeon Graphics     | 3         | 0.92%   |
| AMD Ryzen 7 4800HS with Radeon Graphics    | 3         | 0.92%   |
| AMD Ryzen 5 5625U with Radeon Graphics     | 3         | 0.92%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 2         | 0.62%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 2         | 0.62%   |
| Intel Core i7-7Y75 CPU @ 1.30GHz           | 2         | 0.62%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 0.62%   |
| Intel Core i7-4600U CPU @ 2.10GHz          | 2         | 0.62%   |
| Intel Core i7-2670QM CPU @ 2.20GHz         | 2         | 0.62%   |
| Intel Core i7-2630QM CPU @ 2.00GHz         | 2         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 91        | 28%     |
| Intel Core i7      | 66        | 20.31%  |
| Other              | 56        | 17.23%  |
| AMD Ryzen 7        | 20        | 6.15%   |
| AMD Ryzen 5        | 13        | 4%      |
| Intel Core i3      | 12        | 3.69%   |
| Intel Celeron      | 11        | 3.38%   |
| Intel Pentium      | 9         | 2.77%   |
| Intel Atom         | 8         | 2.46%   |
| Intel Core 2 Duo   | 6         | 1.85%   |
| AMD Ryzen 9        | 6         | 1.85%   |
| AMD Ryzen 7 PRO    | 6         | 1.85%   |
| Intel Genuine      | 4         | 1.23%   |
| AMD Ryzen 3        | 3         | 0.92%   |
| Intel Xeon         | 1         | 0.31%   |
| Intel Pentium M    | 1         | 0.31%   |
| Intel Pentium Dual | 1         | 0.31%   |
| Intel Core m7      | 1         | 0.31%   |
| Intel Core 2 Solo  | 1         | 0.31%   |
| Intel Core 2       | 1         | 0.31%   |
| AMD Turion 64 X2   | 1         | 0.31%   |
| AMD Ryzen 3 PRO    | 1         | 0.31%   |
| AMD FX             | 1         | 0.31%   |
| AMD Embedded       | 1         | 0.31%   |
| AMD E2             | 1         | 0.31%   |
| AMD E              | 1         | 0.31%   |
| AMD Athlon         | 1         | 0.31%   |
| AMD A6             | 1         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 121       | 37.23%  |
| 2      | 115       | 35.38%  |
| 8      | 33        | 10.15%  |
| 6      | 21        | 6.46%   |
| 12     | 14        | 4.31%   |
| 10     | 8         | 2.46%   |
| 1      | 7         | 2.15%   |
| 14     | 4         | 1.23%   |
| 16     | 2         | 0.62%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 325       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 265       | 81.54%  |
| 1      | 60        | 18.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 321       | 98.77%  |
| 32-bit         | 3         | 0.92%   |
| Unknown        | 1         | 0.31%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 129       | 38.05%  |
| 0x306a9    | 16        | 4.72%   |
| 0x806c1    | 14        | 4.13%   |
| 0x206a7    | 13        | 3.83%   |
| 0x40651    | 12        | 3.54%   |
| 0x806ea    | 10        | 2.95%   |
| 0x0a50000c | 10        | 2.95%   |
| 0x906e9    | 8         | 2.36%   |
| 0x806eb    | 8         | 2.36%   |
| 0x806ec    | 7         | 2.06%   |
| 0x806e9    | 7         | 2.06%   |
| 0x406e3    | 7         | 2.06%   |
| 0x906a3    | 6         | 1.77%   |
| 0x306d4    | 6         | 1.77%   |
| 0x20655    | 6         | 1.77%   |
| 0x906ea    | 5         | 1.47%   |
| 0x906a4    | 5         | 1.47%   |
| 0x506e3    | 5         | 1.47%   |
| 0x08600106 | 5         | 1.47%   |
| 0x706e5    | 4         | 1.18%   |
| 0x08608103 | 4         | 1.18%   |
| 0x706a8    | 3         | 0.88%   |
| 0x6fd      | 3         | 0.88%   |
| 0x1067a    | 3         | 0.88%   |
| 0x906ed    | 2         | 0.59%   |
| 0x406c4    | 2         | 0.59%   |
| 0x306c3    | 2         | 0.59%   |
| 0x30678    | 2         | 0.59%   |
| 0x106c2    | 2         | 0.59%   |
| 0x0a601203 | 2         | 0.59%   |
| 0x08600104 | 2         | 0.59%   |
| 0x08108109 | 2         | 0.59%   |
| 0x06006705 | 2         | 0.59%   |
| 0xb06a2    | 1         | 0.29%   |
| 0x806d1    | 1         | 0.29%   |
| 0x706a1    | 1         | 0.29%   |
| 0x506c9    | 1         | 0.29%   |
| 0x406c3    | 1         | 0.29%   |
| 0x40661    | 1         | 0.29%   |
| 0x306a8    | 1         | 0.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 70        | 21.47%  |
| Unknown          | 33        | 10.12%  |
| IvyBridge        | 24        | 7.36%   |
| Haswell          | 24        | 7.36%   |
| TigerLake        | 20        | 6.13%   |
| Alderlake Hybrid | 19        | 5.83%   |
| Skylake          | 18        | 5.52%   |
| SandyBridge      | 17        | 5.21%   |
| Zen 3            | 16        | 4.91%   |
| Zen 2            | 12        | 3.68%   |
| Westmere         | 12        | 3.68%   |
| Silvermont       | 8         | 2.45%   |
| IceLake          | 8         | 2.45%   |
| Broadwell        | 8         | 2.45%   |
| Penryn           | 7         | 2.15%   |
| Core             | 5         | 1.53%   |
| Goldmont plus    | 4         | 1.23%   |
| Excavator        | 4         | 1.23%   |
| Zen+             | 3         | 0.92%   |
| Bonnell          | 3         | 0.92%   |
| Zen              | 2         | 0.61%   |
| Goldmont         | 2         | 0.61%   |
| CometLake        | 2         | 0.61%   |
| Bobcat           | 2         | 0.61%   |
| P6               | 1         | 0.31%   |
| Nehalem          | 1         | 0.31%   |
| K8 Hammer        | 1         | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 245       | 53.73%  |
| Nvidia | 122       | 26.75%  |
| AMD    | 89        | 19.52%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 4.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 19        | 4.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 19        | 4.1%    |
| Intel UHD Graphics 620                                                                   | 15        | 3.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 3.24%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 3.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 2.59%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 12        | 2.59%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 11        | 2.38%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 2.38%   |
| Intel HD Graphics 630                                                                    | 9         | 1.94%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 1.94%   |
| Intel HD Graphics 620                                                                    | 8         | 1.73%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.73%   |
| Intel HD Graphics 530                                                                    | 8         | 1.73%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.51%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 6         | 1.3%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 1.3%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 1.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 1.3%    |
| AMD Lucienne                                                                             | 6         | 1.3%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 1.08%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 1.08%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 5         | 1.08%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 5         | 1.08%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 5         | 1.08%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 1.08%   |
| AMD Barcelo                                                                              | 5         | 1.08%   |
| Nvidia GP107M [GeForce MX350]                                                            | 4         | 0.86%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 4         | 0.86%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 0.86%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.86%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 4         | 0.86%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 4         | 0.86%   |
| AMD Phoenix1                                                                             | 4         | 0.86%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 4         | 0.86%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 127       | 38.84%  |
| Intel + Nvidia | 100       | 30.58%  |
| 1 x AMD        | 56        | 17.13%  |
| Intel + AMD    | 19        | 5.81%   |
| AMD + Nvidia   | 12        | 3.67%   |
| 1 x Nvidia     | 10        | 3.06%   |
| 2 x AMD        | 2         | 0.61%   |
| 2 x Intel      | 1         | 0.31%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 261       | 78.38%  |
| Proprietary | 61        | 18.32%  |
| Unknown     | 11        | 3.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 213       | 63.96%  |
| 0.01-0.5   | 42        | 12.61%  |
| 1.01-2.0   | 41        | 12.31%  |
| 3.01-4.0   | 13        | 3.9%    |
| 0.51-1.0   | 13        | 3.9%    |
| 5.01-6.0   | 8         | 2.4%    |
| 7.01-8.0   | 2         | 0.6%    |
| 8.01-16.0  | 1         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 79        | 21.18%  |
| Chimei Innolux          | 52        | 13.94%  |
| BOE                     | 51        | 13.67%  |
| LG Display              | 50        | 13.4%   |
| Samsung Electronics     | 20        | 5.36%   |
| Dell                    | 10        | 2.68%   |
| Ancor Communications    | 10        | 2.68%   |
| BenQ                    | 9         | 2.41%   |
| Acer                    | 9         | 2.41%   |
| PANDA                   | 7         | 1.88%   |
| ViewSonic               | 6         | 1.61%   |
| Valve                   | 6         | 1.61%   |
| Sharp                   | 6         | 1.61%   |
| Lenovo                  | 6         | 1.61%   |
| Philips                 | 5         | 1.34%   |
| AOC                     | 5         | 1.34%   |
| ASUSTek Computer        | 4         | 1.07%   |
| Apple                   | 4         | 1.07%   |
| TMX                     | 3         | 0.8%    |
| InfoVision              | 3         | 0.8%    |
| Goldstar                | 3         | 0.8%    |
| Eizo                    | 3         | 0.8%    |
| Panasonic               | 2         | 0.54%   |
| NEX                     | 2         | 0.54%   |
| LG Philips              | 2         | 0.54%   |
| IPS                     | 2         | 0.54%   |
| CSO                     | 2         | 0.54%   |
| WST                     | 1         | 0.27%   |
| Sony                    | 1         | 0.27%   |
| Olevia                  | 1         | 0.27%   |
| MStar                   | 1         | 0.27%   |
| MSI                     | 1         | 0.27%   |
| Envision Peripherals    | 1         | 0.27%   |
| CPT                     | 1         | 0.27%   |
| CHR                     | 1         | 0.27%   |
| Chi Mei Optoelectronics | 1         | 0.27%   |
| BOE Technology Group    | 1         | 0.27%   |
| AVX                     | 1         | 0.27%   |
| AGT                     | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 9         | 2.38%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 4         | 1.06%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 4         | 1.06%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 4         | 1.06%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 4         | 1.06%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 4         | 1.06%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 3         | 0.79%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 3         | 0.79%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 3         | 0.79%   |
| BOE LCD Monitor BOE0A56 1920x1080 344x194mm 15.5-inch                 | 3         | 0.79%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.79%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.79%   |
| AU Optronics LCD Monitor AUO253D 1920x1080 309x174mm 14.0-inch        | 3         | 0.79%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 527x296mm 23.8-inch          | 3         | 0.79%   |
| Valve ANX7530 U VLV3003 800x1280 100x160mm 7.4-inch                   | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC554E 1024x600 223x125mm 10.1-inch  | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 2         | 0.53%   |
| Philips PHL 288P6L PHL08F2 3840x2160 621x341mm 27.9-inch              | 2         | 0.53%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 2         | 0.53%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 2         | 0.53%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 2         | 0.53%   |
| LG Display LCD Monitor LGD06F9 1920x1200 302x189mm 14.0-inch          | 2         | 0.53%   |
| LG Display LCD Monitor LGD06CA 1920x1080 309x174mm 14.0-inch          | 2         | 0.53%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch          | 2         | 0.53%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                     | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch       | 2         | 0.53%   |
| BOE NE135A1M-NY1 BOE0CB4 2880x1920 285x190mm 13.5-inch                | 2         | 0.53%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 2         | 0.53%   |
| BOE LCD Monitor BOE08A6 1920x1080 294x165mm 13.3-inch                 | 2         | 0.53%   |
| BOE LCD Monitor BOE0610 1920x1080 344x193mm 15.5-inch                 | 2         | 0.53%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                     | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 176       | 51.76%  |
| 1366x768 (WXGA)    | 69        | 20.29%  |
| 2560x1440 (QHD)    | 14        | 4.12%   |
| 1920x1200 (WUXGA)  | 14        | 4.12%   |
| 3840x2160 (4K)     | 11        | 3.24%   |
| 2560x1600          | 8         | 2.35%   |
| 800x1280           | 6         | 1.76%   |
| 2880x1800          | 6         | 1.76%   |
| 1600x900 (HD+)     | 6         | 1.76%   |
| 1280x800 (WXGA)    | 4         | 1.18%   |
| 1680x1050 (WSXGA+) | 3         | 0.88%   |
| 1024x600           | 3         | 0.88%   |
| 3200x1800 (QHD+)   | 2         | 0.59%   |
| 2880x1920          | 2         | 0.59%   |
| 2256x1504          | 2         | 0.59%   |
| 2160x1440          | 2         | 0.59%   |
| 3840x1080          | 1         | 0.29%   |
| 3200x2000          | 1         | 0.29%   |
| 3072x1920          | 1         | 0.29%   |
| 2560x1080          | 1         | 0.29%   |
| 2288x1287          | 1         | 0.29%   |
| 2048x1152          | 1         | 0.29%   |
| 1680x945           | 1         | 0.29%   |
| 1600x2560          | 1         | 0.29%   |
| 1440x900 (WXGA+)   | 1         | 0.29%   |
| 1280x720 (HD)      | 1         | 0.29%   |
| 1280x1024 (SXGA)   | 1         | 0.29%   |
| Unknown            | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 105       | 28.07%  |
| 14      | 70        | 18.72%  |
| 13      | 67        | 17.91%  |
| 24      | 23        | 6.15%   |
| 23      | 17        | 4.55%   |
| 27      | 15        | 4.01%   |
| 12      | 11        | 2.94%   |
| 21      | 10        | 2.67%   |
| 17      | 10        | 2.67%   |
| 11      | 9         | 2.41%   |
| 31      | 6         | 1.6%    |
| 16      | 6         | 1.6%    |
| 7       | 6         | 1.6%    |
| 22      | 4         | 1.07%   |
| 18      | 4         | 1.07%   |
| 10      | 3         | 0.8%    |
| Unknown | 2         | 0.53%   |
| 55      | 1         | 0.27%   |
| 52      | 1         | 0.27%   |
| 49      | 1         | 0.27%   |
| 40      | 1         | 0.27%   |
| 34      | 1         | 0.27%   |
| 19      | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 211       | 56.57%  |
| 201-300     | 58        | 15.55%  |
| 501-600     | 52        | 13.94%  |
| 401-500     | 19        | 5.09%   |
| 351-400     | 12        | 3.22%   |
| 601-700     | 8         | 2.14%   |
| 1-100       | 6         | 1.61%   |
| 1001-1500   | 3         | 0.8%    |
| Unknown     | 2         | 0.54%   |
| 801-900     | 1         | 0.27%   |
| 701-800     | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 265       | 83.33%  |
| 16/10   | 40        | 12.58%  |
| 3/2     | 5         | 1.57%   |
| 0.67    | 4         | 1.26%   |
| 0.62    | 2         | 0.63%   |
| 21/9    | 1         | 0.31%   |
| Unknown | 1         | 0.31%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 109       | 29.38%  |
| 101-110        | 105       | 28.3%   |
| 201-250        | 42        | 11.32%  |
| 71-80          | 29        | 7.82%   |
| 301-350        | 15        | 4.04%   |
| 121-130        | 10        | 2.7%    |
| 61-70          | 9         | 2.43%   |
| 51-60          | 9         | 2.43%   |
| 251-300        | 8         | 2.16%   |
| 351-500        | 7         | 1.89%   |
| 1-40           | 6         | 1.62%   |
| 111-120        | 6         | 1.62%   |
| 141-150        | 4         | 1.08%   |
| More than 1000 | 3         | 0.81%   |
| 41-50          | 3         | 0.81%   |
| 151-200        | 2         | 0.54%   |
| Unknown        | 2         | 0.54%   |
| 501-1000       | 1         | 0.27%   |
| 91-100         | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 158       | 42.82%  |
| 101-120       | 79        | 21.41%  |
| 51-100        | 61        | 16.53%  |
| 161-240       | 51        | 13.82%  |
| More than 240 | 15        | 4.07%   |
| 1-50          | 3         | 0.81%   |
| Unknown       | 2         | 0.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 252       | 76.13%  |
| 2     | 61        | 18.43%  |
| 0     | 12        | 3.63%   |
| 3     | 6         | 1.81%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 185       | 35.99%  |
| Realtek Semiconductor                  | 160       | 31.13%  |
| Qualcomm Atheros                       | 69        | 13.42%  |
| Broadcom                               | 26        | 5.06%   |
| MediaTek                               | 23        | 4.47%   |
| Broadcom Limited                       | 11        | 2.14%   |
| ASIX Electronics                       | 8         | 1.56%   |
| Ralink                                 | 5         | 0.97%   |
| TP-Link                                | 3         | 0.58%   |
| Qualcomm                               | 3         | 0.58%   |
| OPPO Electronics                       | 3         | 0.58%   |
| Marvell Technology Group               | 3         | 0.58%   |
| Edimax Technology                      | 2         | 0.39%   |
| D-Link                                 | 2         | 0.39%   |
| U-Blox                                 | 1         | 0.19%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.19%   |
| Samsung Electronics                    | 1         | 0.19%   |
| Ralink Technology                      | 1         | 0.19%   |
| Qualcomm Technologies                  | 1         | 0.19%   |
| Qualcomm Atheros Communications        | 1         | 0.19%   |
| Nvidia                                 | 1         | 0.19%   |
| Microchip Technology                   | 1         | 0.19%   |
| Lenovo                                 | 1         | 0.19%   |
| Google                                 | 1         | 0.19%   |
| ASUSTek Computer                       | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 104       | 17.57%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 19        | 3.21%   |
| Intel Wireless 8265 / 8275                                             | 18        | 3.04%   |
| Intel Wi-Fi 6 AX201                                                    | 18        | 3.04%   |
| Intel Wi-Fi 6 AX200                                                    | 18        | 3.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 14        | 2.36%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 14        | 2.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 11        | 1.86%   |
| Intel Wireless 7260                                                    | 11        | 1.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 10        | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 9         | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 9         | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 9         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 8         | 1.35%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 8         | 1.35%   |
| Intel Wireless 7265                                                    | 8         | 1.35%   |
| Intel Wireless 3165                                                    | 8         | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 7         | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7         | 1.18%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 7         | 1.18%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 6         | 1.01%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 1.01%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 6         | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6         | 1.01%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 6         | 1.01%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 6         | 1.01%   |
| Intel Ethernet Connection I218-LM                                      | 6         | 1.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 1.01%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 6         | 1.01%   |
| ASIX AX88179 Gigabit Ethernet                                          | 6         | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5         | 0.84%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 5         | 0.84%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 5         | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 5         | 0.84%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 5         | 0.84%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 5         | 0.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 5         | 0.84%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 4         | 0.68%   |
| Intel Wireless 8260                                                    | 4         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 178       | 55.63%  |
| Qualcomm Atheros                | 49        | 15.31%  |
| Realtek Semiconductor           | 29        | 9.06%   |
| MediaTek                        | 20        | 6.25%   |
| Broadcom                        | 18        | 5.63%   |
| Broadcom Limited                | 8         | 2.5%    |
| Ralink                          | 5         | 1.56%   |
| Qualcomm                        | 3         | 0.94%   |
| TP-Link                         | 2         | 0.63%   |
| Edimax Technology               | 2         | 0.63%   |
| D-Link                          | 2         | 0.63%   |
| Ralink Technology               | 1         | 0.31%   |
| Qualcomm Technologies           | 1         | 0.31%   |
| Qualcomm Atheros Communications | 1         | 0.31%   |
| ASUSTek Computer                | 1         | 0.31%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 18        | 5.61%   |
| Intel Wi-Fi 6 AX201                                            | 18        | 5.61%   |
| Intel Wi-Fi 6 AX200                                            | 18        | 5.61%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 14        | 4.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 11        | 3.43%   |
| Intel Wireless 7260                                            | 11        | 3.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 10        | 3.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 2.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 9         | 2.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 9         | 2.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 2.49%   |
| Intel Wireless 7265                                            | 8         | 2.49%   |
| Intel Wireless 3165                                            | 8         | 2.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 2.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 2.18%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 7         | 2.18%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 6         | 1.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 1.87%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 6         | 1.87%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 6         | 1.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 1.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5         | 1.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 5         | 1.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 1.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 1.56%   |
| Intel Wireless 8260                                            | 4         | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 1.25%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 1.25%   |
| Broadcom BCM43225 802.11b/g/n                                  | 4         | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.25%   |
| Realtek 802.11ac NIC                                           | 3         | 0.93%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.93%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 3         | 0.93%   |
| Intel Wireless 3160                                            | 3         | 0.93%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 0.62%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 2         | 0.62%   |
| Intel WiFi Link 5100                                           | 2         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 145       | 55.34%  |
| Intel                                  | 47        | 17.94%  |
| Qualcomm Atheros                       | 33        | 12.6%   |
| Broadcom                               | 10        | 3.82%   |
| ASIX Electronics                       | 8         | 3.05%   |
| OPPO Electronics                       | 3         | 1.15%   |
| MediaTek                               | 3         | 1.15%   |
| Marvell Technology Group               | 3         | 1.15%   |
| Broadcom Limited                       | 3         | 1.15%   |
| TP-Link                                | 1         | 0.38%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.38%   |
| Samsung Electronics                    | 1         | 0.38%   |
| Nvidia                                 | 1         | 0.38%   |
| Microchip Technology                   | 1         | 0.38%   |
| Lenovo                                 | 1         | 0.38%   |
| Google                                 | 1         | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 104       | 38.52%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 19        | 7.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 14        | 5.19%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 2.22%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 6         | 2.22%   |
| Intel Ethernet Connection I218-LM                                      | 6         | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 2.22%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 6         | 2.22%   |
| ASIX AX88179 Gigabit Ethernet                                          | 6         | 2.22%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 5         | 1.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 5         | 1.85%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 1.85%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 4         | 1.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3         | 1.11%   |
| OPPO OnePlus Nord 4                                                    | 3         | 1.11%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 3         | 1.11%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 1.11%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.11%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.74%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 0.74%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.74%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.74%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                   | 2         | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.74%   |
| Intel Ethernet Connection (23) I219-V                                  | 2         | 0.74%   |
| Intel Ethernet Connection (23) I219-LM                                 | 2         | 0.74%   |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                      | 2         | 0.74%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express         | 2         | 0.74%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.37%   |
| Sony Ericsson Mobile AB XQ-BT52                                        | 1         | 0.37%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.37%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.37%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 1         | 0.37%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.37%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.37%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 310       | 55.86%  |
| Ethernet | 244       | 43.96%  |
| Modem    | 1         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 251       | 72.54%  |
| Ethernet | 95        | 27.46%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 213       | 65.54%  |
| 1     | 106       | 32.62%  |
| 0     | 4         | 1.23%   |
| 5     | 1         | 0.31%   |
| 3     | 1         | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 279       | 84.8%   |
| Yes  | 50        | 15.2%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 157       | 54.7%   |
| IMC Networks                    | 19        | 6.62%   |
| Foxconn / Hon Hai               | 19        | 6.62%   |
| Broadcom                        | 17        | 5.92%   |
| Realtek Semiconductor           | 16        | 5.57%   |
| Qualcomm Atheros Communications | 15        | 5.23%   |
| Lite-On Technology              | 14        | 4.88%   |
| Apple                           | 5         | 1.74%   |
| MediaTek                        | 4         | 1.39%   |
| Hewlett-Packard                 | 4         | 1.39%   |
| Toshiba                         | 3         | 1.05%   |
| Realtek                         | 3         | 1.05%   |
| Ralink                          | 3         | 1.05%   |
| USI                             | 2         | 0.7%    |
| ASUSTek Computer                | 2         | 0.7%    |
| Opticis                         | 1         | 0.35%   |
| Micro Star International        | 1         | 0.35%   |
| Dell                            | 1         | 0.35%   |
| Alps Electric                   | 1         | 0.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 55        | 19.16%  |
| Intel AX201 Bluetooth                             | 32        | 11.15%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 21        | 7.32%   |
| Intel AX200 Bluetooth                             | 18        | 6.27%   |
| Intel AX211 Bluetooth                             | 15        | 5.23%   |
| Realtek Bluetooth Radio                           | 14        | 4.88%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 6         | 2.09%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 6         | 2.09%   |
| Intel AX210 Bluetooth                             | 6         | 2.09%   |
| IMC Networks Wireless_Device                      | 5         | 1.74%   |
| IMC Networks Bluetooth Radio                      | 5         | 1.74%   |
| Foxconn / Hon Hai Wireless_Device                 | 5         | 1.74%   |
| Foxconn / Hon Hai Bluetooth Device                | 5         | 1.74%   |
| MediaTek Wireless_Device                          | 4         | 1.39%   |
| Lite-On Wireless_Device                           | 4         | 1.39%   |
| Intel Wireless-AC 3168 Bluetooth                  | 4         | 1.39%   |
| Apple Bluetooth Host Controller                   | 4         | 1.39%   |
| Realtek Bluetooth Radio                           | 3         | 1.05%   |
| Ralink RT3290 Bluetooth                           | 3         | 1.05%   |
| Qualcomm Atheros  Bluetooth Device                | 3         | 1.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 3         | 1.05%   |
| Lite-On Bluetooth Device                          | 3         | 1.05%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 3         | 1.05%   |
| IMC Networks Bluetooth Device                     | 3         | 1.05%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 3         | 1.05%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth       | 3         | 1.05%   |
| Foxconn / Hon Hai Acer Bluetooth module           | 3         | 1.05%   |
| Broadcom BCM2045B (BDC-2.1)                       | 3         | 1.05%   |
| Toshiba Bluetooth USB Host Controller             | 2         | 0.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 2         | 0.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 2         | 0.7%    |
| HP Broadcom 2070 Bluetooth Combo                  | 2         | 0.7%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 2         | 0.7%    |
| Broadcom HP Portable Bumble Bee                   | 2         | 0.7%    |
| Broadcom Bluetooth                                | 2         | 0.7%    |
| Broadcom BCM20702A0                               | 2         | 0.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 2         | 0.7%    |
| Broadcom BCM2045 Bluetooth                        | 2         | 0.7%    |
| USI Bluetooth Module BCM92070                     | 1         | 0.35%   |
| USI Bluetooth Device                              | 1         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 254       | 64.8%   |
| AMD                     | 73        | 18.62%  |
| Nvidia                  | 50        | 12.76%  |
| C-Media Electronics     | 3         | 0.77%   |
| Texas Instruments       | 2         | 0.51%   |
| Dell                    | 2         | 0.51%   |
| ASUSTek Computer        | 2         | 0.51%   |
| Realtek Semiconductor   | 1         | 0.26%   |
| Logitech                | 1         | 0.26%   |
| GN Netcom               | 1         | 0.26%   |
| Generalplus Technology  | 1         | 0.26%   |
| ESS Technology          | 1         | 0.26%   |
| Cambridge Silicon Radio | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 51        | 10.58%  |
| Intel Sunrise Point-LP HD Audio                                            | 35        | 7.26%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 34        | 7.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 25        | 5.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 20        | 4.15%   |
| Intel Haswell-ULT HD Audio Controller                                      | 20        | 4.15%   |
| Intel 8 Series HD Audio Controller                                         | 20        | 4.15%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 19        | 3.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 3.32%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 16        | 3.32%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 15        | 3.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 14        | 2.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 13        | 2.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 1.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 1.66%   |
| Intel CM238 HD Audio Controller                                            | 8         | 1.66%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 1.66%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 1.45%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 1.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 1.45%   |
| Nvidia TU116 High Definition Audio Controller                              | 6         | 1.24%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 1.24%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 6         | 1.24%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 1.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 0.83%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 0.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 0.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 0.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 0.83%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 4         | 0.83%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 0.83%   |
| Nvidia High Definition Audio Controller                                    | 3         | 0.62%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 0.62%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 0.62%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.41%   |
| Intel USB PnP Sound Device                                                 | 2         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 62        | 23.4%   |
| Samsung Electronics | 54        | 20.38%  |
| Micron Technology   | 39        | 14.72%  |
| Kingston            | 31        | 11.7%   |
| Crucial             | 22        | 8.3%    |
| Transcend           | 12        | 4.53%   |
| Unknown             | 11        | 4.15%   |
| A-DATA Technology   | 8         | 3.02%   |
| Elpida              | 3         | 1.13%   |
| Apacer              | 3         | 1.13%   |
| Unknown (ABCD)      | 2         | 0.75%   |
| Team                | 2         | 0.75%   |
| Ramaxel Technology  | 2         | 0.75%   |
| Nanya Technology    | 2         | 0.75%   |
| Goldkey             | 2         | 0.75%   |
| G-Alantic           | 2         | 0.75%   |
| Unknown (08AE)      | 1         | 0.38%   |
| PNY                 | 1         | 0.38%   |
| Patriot             | 1         | 0.38%   |
| Lexar               | 1         | 0.38%   |
| G.Skill             | 1         | 0.38%   |
| Avant               | 1         | 0.38%   |
| ASint Technology    | 1         | 0.38%   |
| Unknown             | 1         | 0.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 1.76%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 1.41%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.06%   |
| Samsung RAM K4UBE3D4AA-MGCR 8GB SODIMM LPDDR4 4266MT/s              | 3         | 1.06%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 3         | 1.06%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 3         | 1.06%   |
| Kingston RAM 9905624-033.A00G 8GB SODIMM DDR4 2400MT/s              | 3         | 1.06%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 2         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 2         | 0.7%    |
| Transcend RAM Module 16GB SODIMM DDR4 3200MT/s                      | 2         | 0.7%    |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 2         | 0.7%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.7%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 2         | 0.7%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 2         | 0.7%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 0.7%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 2         | 0.7%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 2         | 0.7%    |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 2         | 0.7%    |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s    | 2         | 0.7%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 2         | 0.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.7%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.7%    |
| Samsung RAM M471A1K43CB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.7%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 0.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.7%    |
| Micron RAM MT40A1G16TB-062E:F 8GB SODIMM DDR4 3200MT/s              | 2         | 0.7%    |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s               | 2         | 0.7%    |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.7%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.7%    |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2667MT/s               | 2         | 0.7%    |
| Kingston RAM ACR16D3LS1KNG/4G 4GB SODIMM DDR3 1600MT/s              | 2         | 0.7%    |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 2667MT/s             | 2         | 0.7%    |
| Kingston RAM 9905700-046.A00G 16GB SODIMM DDR4 3200MT/s             | 2         | 0.7%    |
| G-Alantic RAM D4SS12161SH26A-C 4GB SODIMM DDR4 2133MT/s             | 2         | 0.7%    |
| Crucial RAM CT8G4SFS8266.M8FE 8GB SODIMM DDR4 2667MT/s              | 2         | 0.7%    |
| Crucial RAM CT8G4SFS632A.C4FE 8GB SODIMM DDR4 3200MT/s              | 2         | 0.7%    |
| Crucial RAM CT16G4SFRA32A.C8FE 16GB SODIMM DDR4 3200MT/s            | 2         | 0.7%    |
| Crucial RAM CT16G4SFD832A.M16FR 16GB SODIMM DDR4 3200MT/s           | 2         | 0.7%    |
| Crucial RAM CT16G4SFD8266.M16FE 16GB SODIMM DDR4 2667MT/s           | 2         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 106       | 48.85%  |
| DDR3    | 50        | 23.04%  |
| LPDDR4  | 18        | 8.29%   |
| LPDDR5  | 13        | 5.99%   |
| LPDDR3  | 11        | 5.07%   |
| DDR5    | 10        | 4.61%   |
| DDR2    | 4         | 1.84%   |
| SDRAM   | 3         | 1.38%   |
| Unknown | 2         | 0.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 173       | 80.84%  |
| Row Of Chips | 37        | 17.29%  |
| DIMM         | 2         | 0.93%   |
| Chip         | 1         | 0.47%   |
| Unknown      | 1         | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 98        | 41%     |
| 4096  | 61        | 25.52%  |
| 16384 | 46        | 19.25%  |
| 32768 | 15        | 6.28%   |
| 2048  | 15        | 6.28%   |
| 1024  | 3         | 1.26%   |
| 8072  | 1         | 0.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 57        | 24.89%  |
| 2667    | 40        | 17.47%  |
| 1600    | 38        | 16.59%  |
| 2400    | 15        | 6.55%   |
| 2133    | 13        | 5.68%   |
| 6400    | 11        | 4.8%    |
| 1334    | 8         | 3.49%   |
| 4800    | 7         | 3.06%   |
| 4266    | 6         | 2.62%   |
| 5600    | 5         | 2.18%   |
| 4267    | 5         | 2.18%   |
| 1867    | 4         | 1.75%   |
| 7500    | 2         | 0.87%   |
| 4199    | 2         | 0.87%   |
| 1333    | 2         | 0.87%   |
| 800     | 2         | 0.87%   |
| 533     | 2         | 0.87%   |
| 8400    | 1         | 0.44%   |
| 3733    | 1         | 0.44%   |
| 3266    | 1         | 0.44%   |
| 2666    | 1         | 0.44%   |
| 2000    | 1         | 0.44%   |
| 1067    | 1         | 0.44%   |
| 1066    | 1         | 0.44%   |
| 975     | 1         | 0.44%   |
| 667     | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Seiko Epson L3110 Series | 1         | 100%    |

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
| Chicony Electronics                    | 75        | 27.68%  |
| IMC Networks                           | 41        | 15.13%  |
| Realtek Semiconductor                  | 31        | 11.44%  |
| Bison Electronics                      | 20        | 7.38%   |
| Quanta                                 | 15        | 5.54%   |
| Sunplus Innovation Technology          | 13        | 4.8%    |
| Microdia                               | 11        | 4.06%   |
| Suyin                                  | 9         | 3.32%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.58%   |
| Luxvisions Innotech Limited            | 6         | 2.21%   |
| Syntek                                 | 5         | 1.85%   |
| Sonix Technology                       | 4         | 1.48%   |
| ALi                                    | 4         | 1.48%   |
| Acer                                   | 4         | 1.48%   |
| Lite-On Technology                     | 3         | 1.11%   |
| Apple                                  | 3         | 1.11%   |
| Sunplus Technology                     | 2         | 0.74%   |
| Silicon Motion                         | 2         | 0.74%   |
| Ricoh                                  | 2         | 0.74%   |
| Lenovo                                 | 2         | 0.74%   |
| Importek                               | 2         | 0.74%   |
| SunplusIT                              | 1         | 0.37%   |
| Shinetech                              | 1         | 0.37%   |
| Samsung Electronics                    | 1         | 0.37%   |
| Novatek Microelectronics               | 1         | 0.37%   |
| Logitech                               | 1         | 0.37%   |
| Google                                 | 1         | 0.37%   |
| Generalplus Technology                 | 1         | 0.37%   |
| Framework                              | 1         | 0.37%   |
| Foxconn / Hon Hai                      | 1         | 0.37%   |
| Aspeed Technology                      | 1         | 0.37%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 21        | 7.69%   |
| Chicony Integrated Camera                                                  | 18        | 6.59%   |
| Chicony HD WebCam                                                          | 12        | 4.4%    |
| IMC Networks Integrated Camera                                             | 9         | 3.3%    |
| Realtek Integrated_Webcam_HD                                               | 8         | 2.93%   |
| Bison HD Webcam                                                            | 8         | 2.93%   |
| Sunplus HD WebCam                                                          | 6         | 2.2%    |
| Chicony HP HD Camera                                                       | 6         | 2.2%    |
| Chicony HD User Facing                                                     | 6         | 2.2%    |
| Realtek USB Camera                                                         | 4         | 1.47%   |
| Quanta HD User Facing                                                      | 4         | 1.47%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 1.47%   |
| Microdia Integrated_Webcam_FHD                                             | 4         | 1.47%   |
| Chicony USB2.0 HD UVC WebCam                                               | 4         | 1.47%   |
| Chicony Lenovo EasyCamera                                                  | 4         | 1.47%   |
| Bison Integrated Camera                                                    | 4         | 1.47%   |
| ALi Gateway Webcam                                                         | 4         | 1.47%   |
| Syntek Integrated Camera                                                   | 3         | 1.1%    |
| Sonix USB2.0 HD UVC WebCam                                                 | 3         | 1.1%    |
| Realtek USB2.0 HD UVC WebCam                                               | 3         | 1.1%    |
| Realtek HD WebCam                                                          | 3         | 1.1%    |
| Quanta ACER HD User Facing                                                 | 3         | 1.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 1.1%    |
| Chicony USB2.0 Camera                                                      | 3         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 1.1%    |
| Suyin Acer/Lenovo Webcam [CN0316]                                          | 2         | 0.73%   |
| Suyin 1.3M HD WebCam                                                       | 2         | 0.73%   |
| Sunplus 1.3M HD WebCam                                                     | 2         | 0.73%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 0.73%   |
| Sunplus Integrated_Webcam_FHD                                              | 2         | 0.73%   |
| Realtek USB2.0 camera                                                      | 2         | 0.73%   |
| Realtek HD Webcam - Realtek                                                | 2         | 0.73%   |
| Quanta HP HD Camera                                                        | 2         | 0.73%   |
| Luxvisions Innotech Limited Integrated Camera                              | 2         | 0.73%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 2         | 0.73%   |
| Lenovo Integrated Webcam [R5U877]                                          | 2         | 0.73%   |
| IMC Networks UVC VGA Webcam                                                | 2         | 0.73%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 2         | 0.73%   |
| Chicony Webcam                                                             | 2         | 0.73%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 0.73%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 18        | 28.13%  |
| Validity Sensors                   | 12        | 18.75%  |
| LighTuning Technology              | 11        | 17.19%  |
| Shenzhen Goodix Technology         | 9         | 14.06%  |
| Elan Microelectronics              | 6         | 9.38%   |
| Upek                               | 4         | 6.25%   |
| AuthenTec                          | 3         | 4.69%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 10.94%  |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 9.38%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 6.25%   |
| Elan ELAN:Fingerprint                                                      | 4         | 6.25%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 4.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 4.69%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 4.69%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 4.69%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 3.13%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 3.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 3.13%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 3.13%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 3.13%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 3.13%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 3.13%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.56%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.56%   |
| Synaptics WBDI                                                             | 1         | 1.56%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 1.56%   |
| Synaptics Prometheus Fingerprint Reader                                    | 1         | 1.56%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 1.56%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.56%   |
| Elan WBF Fingerprint Sensor                                                | 1         | 1.56%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 1.56%   |
| AuthenTec AES2810                                                          | 1         | 1.56%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.56%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 8         | 47.06%  |
| Broadcom              | 4         | 23.53%  |
| Upek                  | 2         | 11.76%  |
| SCM Microsystems      | 1         | 5.88%   |
| Lenovo                | 1         | 5.88%   |
| Gemalto (was Gemplus) | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 41.18%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 11.76%  |
| Broadcom 58200                                                               | 2         | 11.76%  |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 5.88%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 5.88%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 5.88%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 202       | 59.76%  |
| 1     | 106       | 31.36%  |
| 2     | 25        | 7.4%    |
| 3     | 3         | 0.89%   |
| 9     | 1         | 0.3%    |
| 4     | 1         | 0.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 64        | 39.75%  |
| Graphics card            | 39        | 24.22%  |
| Chipcard                 | 13        | 8.07%   |
| Net/wireless             | 10        | 6.21%   |
| Camera                   | 10        | 6.21%   |
| Multimedia controller    | 7         | 4.35%   |
| Card reader              | 6         | 3.73%   |
| Bluetooth                | 5         | 3.11%   |
| Sound                    | 2         | 1.24%   |
| Net/ethernet             | 2         | 1.24%   |
| Communication controller | 2         | 1.24%   |
| Storage/nvme             | 1         | 0.62%   |

